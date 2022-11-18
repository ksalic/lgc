<template>
  <div style="position: relative" v-if="document">
    <style>
      .sitewide-banner {
        background-color: #5bc0d4;
        text-align: center;
        color: white;
        font-size: 16px;
        margin: 30px;
        box-sizing: border-box;
        padding: 20px;
        max-width: 1315px;
        margin: 30px auto;
      }
      .sitewide-banner p {
        text-align: center;
        color: white !important;
        font-size: 16px;
      }
    </style>
    <br-manage-content-button :content="document" />
    <div class="sitewide-banner outline" v-if="document?.getData()?.text" v-html="document.getData().text.value" />
  </div>
</template>

<script lang="ts">
import { ContainerItem, Page } from '@bloomreach/spa-sdk';
import { Component, Prop, Vue } from 'nuxt-property-decorator';

@Component({
  computed: {
    document(this: BrFreeText) {
      return this.page?.getContent(this.component.getProperties<any>()?.document);
    },
  },

  name: 'br-freetext',
})
export default class BrFreeText extends Vue {
  @Prop() component!: ContainerItem;

  @Prop() page!: Page;
}
</script>
