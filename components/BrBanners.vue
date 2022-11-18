<!--
  Copyright 2020 Bloomreach

  Licensed under the Apache License, Version 2.0 (the "License");
  you may not use this file except in compliance with the License.
  You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

  Unless required by applicable law or agreed to in writing, software
  distributed under the License is distributed on an "AS IS" BASIS,
  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
  See the License for the specific language governing permissions and
  limitations under the License.
  -->

<template>
  <div class="content">
    <div class="container">
      <div :class="{'cta-banners': properties.type === '3-column'}" >
        <div class="wide-banner" v-if="properties.type === 'wide'" v-for="banner in content.banners">
          <img
              :src="page?.getContent(banner.image)?.model?.data?.original?.links?.site?.href"
              class="atfload"
              alt="homepage_desktopCOVID.jpg"
          />
          <div class="wide-banner__content left">
            <h2 class="wide-banner__title uber-heading">{{ banner.title }}</h2>
            <h3 class="wide-banner__subtitle sub-heading-3">{{ banner.subtitle }}</h3>
            <p class="wide-banner__description text">{{ banner.description }}</p> <a
              href="#"
              class="_btn _btn--primary">{{ banner.ctaText }}</a>
          </div>
        </div>
        <div class="cta-banner" v-if="properties.type === '3-column'" v-for="banner in content.banners">
          <div class="cta-banner__img">
            <img
                :src="page?.getContent(banner.image)?.model?.data?.original?.links?.site?.href"
             alt="TRChomecta-min.jpeg"/>
          </div>
          <div class="cta-banner__content"><h3 class="cta-banner__title sub-heading-3">{{ banner.title }}</h3>
            <div class="cta-banner__bottom"><p class="cta-banner__description text">{{ banner.description }}</p> <a
                href="https://www.lgcstandards.com/GB/en/Toronto-Research-Chemicals/cat/279854"
                class="cta-banner__link _btn _btn--primary">{{ banner.ctaText }}</a></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import {ContainerItem, Page} from '@bloomreach/spa-sdk';
import {Component, Prop, Vue} from 'nuxt-property-decorator';

@Component({
  computed: {
    content(this: BrBanners) {
      return this.component.getContent<any>(this.page);
    },
    properties(this: BrBanners) {
      return this.component.getProperties<any>();
    },
  },

  name: 'br-freetext',
})
export default class BrBanners extends Vue {
  @Prop() component!: ContainerItem;

  @Prop() page!: Page;
}
</script>
