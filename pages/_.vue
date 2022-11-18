<!--
  Copyright 2020-2022 Bloomreach

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
  <br-page :configuration="configuration" :mapping="mapping" :page="page">
    <template #default="props">
      <template v-if="props.page">
        <header id="mainHeader">
          <div class="header-core header-core_desktop">
            <div class="header-core__content"><a :href="props.page.getUrl()"><img class="header-core__logo" title="" alt=""
                                                                         src="/medias/sys_master/root/h6c/hfb/10397484711966/10397484711966.jpg">
            </a>
            </div>
          </div>

          <div class="desktop_megamenu_navigation">
            <br-component component="menu" />

          </div>
        </header>
        <div>
          <br-component component="main" />
        </div>
        <footer id="footer" class="footer">
          <section class="footer-social">
            <div class="footer-social__content"><h2 class="footer-social__heading">Stay in the know with the latest
              updates</h2>
              <div class="footer-social__by-sections">
                <section class="social-media"><h3 class="social-media__heading">By following us on social media</h3>
                  <ul class="social-media__social-list">
                    <li class="social-media__social">
                      <div class="social-media__social-popup-container social-media__social-popup-container--linkedin">
                        <ul class="social-media__social-popup">
                          <li class="social-media__social-popup-link social-media__social-popup-link_linkedin">
                            <a href="https://www.linkedin.com/company/lgc-standards/" target="_blank"
                               rel="noopener noreferrer">LGC Standards</a></li>
                          <li class="social-media__social-popup-link social-media__social-popup-link_linkedin">
                            <a href="https://www.linkedin.com/showcase/lgc-mikromol/" target="_blank"
                               rel="noopener noreferrer">Mikromol</a></li>
                          <li class="social-media__social-popup-link social-media__social-popup-link_linkedin">
                            <a href="https://www.linkedin.com/company/dr-ehrenstorfer/" target="_blank"
                               rel="noopener noreferrer">Dr. Ehrenstorfer</a></li>
                          <li class="social-media__social-popup-link social-media__social-popup-link_linkedin">
                            <a href="https://www.linkedin.com/company/lgc-standards-logical/"
                               target="_blank" rel="noopener noreferrer">LoGiCal</a></li>
                          <li class="social-media__social-popup-link social-media__social-popup-link_linkedin">
                            <a href="https://www.linkedin.com/company/lgc-armi-standards/"
                               target="_blank" rel="noopener noreferrer">ARMI</a></li>
                          <li class="social-media__social-popup-link social-media__social-popup-link_linkedin">
                            <a href="https://www.linkedin.com/company/vhg-labs/" target="_blank"
                               rel="noopener noreferrer">VHG</a></li>
                          <li class="social-media__social-popup-link social-media__social-popup-link_linkedin">
                            <a href="https://www.linkedin.com/company/lgc-axio" target="_blank"
                               rel="noopener noreferrer">AXIO PT</a></li>
                          <li class="social-media__social-popup-link social-media__social-popup-link_linkedin">
                            <a href="https://www.linkedin.com/company/toronto-research-chemicals/"
                               target="_blank" rel="noopener noreferrer">TRC</a></li>
                        </ul>
                      </div>
                      <span class="social-media__social-icon social-media__social-icon_linkedin"></span></li>
                    <li class="social-media__social">
                      <div class="social-media__social-popup-container social-media__social-popup-container--twitter">
                        <ul class="social-media__social-popup">
                          <li class="social-media__social-popup-link social-media__social-popup-link_twitter">
                            <a href="https://twitter.com/LGCStandards" target="_blank"
                               rel="noopener noreferrer">LGC Standards</a></li>
                          <li class="social-media__social-popup-link social-media__social-popup-link_twitter">
                            <a href="https://twitter.com/LGCMikromol" target="_blank"
                               rel="noopener noreferrer">Mikromol</a></li>
                          <li class="social-media__social-popup-link social-media__social-popup-link_twitter">
                            <a href="https://twitter.com/drehrenstorfer" target="_blank"
                               rel="noopener noreferrer">Dr. Ehrenstorfer</a></li>
                          <li class="social-media__social-popup-link social-media__social-popup-link_twitter">
                            <a href="https://twitter.com/LGCLoGiCal" target="_blank"
                               rel="noopener noreferrer">LoGiCal</a></li>
                          <li class="social-media__social-popup-link social-media__social-popup-link_twitter">
                            <a href="https://twitter.com/LGCARMI" target="_blank"
                               rel="noopener noreferrer">ARMI</a></li>
                          <li class="social-media__social-popup-link social-media__social-popup-link_twitter">
                            <a href="https://twitter.com/LGC_VHG" target="_blank"
                               rel="noopener noreferrer">VHG</a></li>
                          <li class="social-media__social-popup-link social-media__social-popup-link_twitter">
                            <a href="https://twitter.com/LGCAXIO" target="_blank"
                               rel="noopener noreferrer">AXIO PT</a></li>
                          <li class="social-media__social-popup-link social-media__social-popup-link_twitter">
                            <a href="https://twitter.com/TRCIncorporated" target="_blank"
                               rel="noopener noreferrer">TRC</a></li>
                        </ul>
                      </div>
                      <span class="social-media__social-icon social-media__social-icon_twitter"></span></li>
                    <li class="social-media__social">
                      <div class="social-media__social-popup-container social-media__social-popup-container--youtube">
                        <ul class="social-media__social-popup">
                          <li class="social-media__social-popup-link social-media__social-popup-link_youtube">
                            <a href="https://www.youtube.com/channel/UCIU8C6lQTnG6W6GnLxBNgog"
                               target="_blank" rel="noopener noreferrer">LGC Standards</a></li>
                        </ul>
                      </div>
                      <span class="social-media__social-icon social-media__social-icon_youtube"></span></li>
                    <li class="social-media__social">
                      <div class="social-media__social-popup-container social-media__social-popup-container--facebook">
                        <ul class="social-media__social-popup">
                          <li class="social-media__social-popup-link social-media__social-popup-link_facebook">
                            <a href="https://en-gb.facebook.com/LGCgroup/" target="_blank"
                               rel="noopener noreferrer">LGC Standards</a></li>
                          <li class="social-media__social-popup-link social-media__social-popup-link_facebook">
                            <a href="https://www.facebook.com/ARMIStandards/" target="_blank"
                               rel="noopener noreferrer">ARMI</a></li>
                          <li class="social-media__social-popup-link social-media__social-popup-link_facebook">
                            <a href="https://www.facebook.com/TRC.LGC/" target="_blank"
                               rel="noopener noreferrer">TRC</a></li>
                        </ul>
                      </div>
                      <span class="social-media__social-icon social-media__social-icon_facebook"></span></li>
                  </ul>
                </section>
                <section class="newsletter"><h3 class="newsletter__heading">By registering for our email
                  newsletter</h3> <a href="https://www.lgcstandards.com/GB/en/Resources/Newsletter"
                                     class="newsletter__email-submit _btn _btn--primary"> Get updates </a>
                </section>
              </div>
            </div>
          </section>
          <div class="footer-navigation">
            <div class="footer-navigation__content">
              <div class="footer-navigation__sections">
                <section class="footer-navigation__section footer-navigation__section_categories">
                  <h2 class="footer-navigation__heading">Products and Services
                    <button class="footer-navigation__mcat-expand"></button>
                  </h2>
                  <ul class="footer-navigation__categories footer-navigation__mobile-mcat-data footer-navigation__mobile-mcat-data-hide">
                    <li class="footer-navigation__category"><a
                        href="https://www.lgcstandards.com/GB/en/cat/323667"
                        class="footer-navigation__category-name">Research Tools</a>
                      <button class="footer-navigation__category-expand"></button>
                      <div class="footer-navigation__subcategories">
                        <ul class="footer-navigation__subcategories-column">
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/322963">COVID-19 research
                            and reference materials</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/323782">Building blocks</a>
                          </li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/323789">Enzyme activators,
                            inhibitors & substrates</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/323794">Chiral
                            molecules</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/323795">Neurochemicals</a>
                          </li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/323797">Carbohydrates</a>
                          </li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/323800">Cross-linkers</a>
                          </li>
                        </ul>
                        <ul class="footer-navigation__subcategories-column">
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/323801">Stable isotope
                            labelled compounds</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/323802">Cannabis-related
                            products</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/323773">Steroids and
                            derivatives</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/323751">Pharmaceutical
                            toxicology</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/323754">Antibiotics</a>
                          </li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/323759">Antimalarials</a>
                          </li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/323763">Antivirals and
                            antiretrovirals</a></li>
                        </ul>
                      </div>
                    </li>
                    <li class="footer-navigation__category"><a
                        href="https://www.lgcstandards.com/GB/en/Food-and-beverage/cat/279493"
                        class="footer-navigation__category-name">Food & Beverage</a>
                      <button class="footer-navigation__category-expand"></button>
                      <div class="footer-navigation__subcategories">
                        <ul class="footer-navigation__subcategories-column">
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Food-and-Beverage/Cannabis-related-compounds/cat/279543">Cannabis-related
                            compounds</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Food-and-Beverage/Dyes-and-metabolites/cat/279550">Dyes
                            & metabolites</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Food-and-Beverage/Allergens/cat/279551">Allergens</a>
                          </li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Food-and-Beverage/Nutritional-composition-compounds/cat/279552">Nutritional
                            composition compounds</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Food-and-Beverage/Food-additives-flavours-and-adulterants/cat/279553">Food
                            additives, flavours & adulterants</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Food-and-Beverage/Mycotoxins/cat/279554">Mycotoxins</a>
                          </li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Food-and-Beverage/Environmental-food-contaminants/cat/279557">Environmental
                            food contaminants</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Food-and-Beverage/Pesticides-and-metabolites/cat/279562">Pesticides
                            & metabolites</a></li>
                        </ul>
                        <ul class="footer-navigation__subcategories-column">
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Food-and-Beverage/Pharmaceutical-and-veterinary-compounds-and-metabolites/cat/279568">Pharma
                            & vet compounds & metabolites</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Food-and-Beverage/Phytochemicals/cat/279569">Phytochemicals</a>
                          </li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Food-and-Beverage/Food-contact-materials/cat/279599">Food
                            contact materials</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Food-and-Beverage/Beverage-reference-materials/cat/279604">Beverage
                            reference materials</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Proficiency-Testing/Food-and-feed-Schemes/cat/280775">Food
                            & beverage proficiency testing</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Food-and-Beverage/Standards-for-food-regulatory-methods/cat/279622">Standards
                            for food regulatory methods</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Food-and-Beverage/Stable-isotope-labelled-compounds/cat/279627">Stable
                            isotope labelled compounds</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Food-and-Beverage/Microbiology/cat/279643">Microbiology</a>
                          </li>
                        </ul>
                      </div>
                    </li>
                    <li class="footer-navigation__category"><a
                        href="https://www.lgcstandards.com/GB/en/Environmental/cat/279494"
                        class="footer-navigation__category-name">Environmental</a>
                      <button class="footer-navigation__category-expand"></button>
                      <div class="footer-navigation__subcategories">
                        <ul class="footer-navigation__subcategories-column">
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Environmental/Stable-isotope-labelled-compounds/cat/279645">Stable
                            isotope labelled compounds</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Environmental/PCBs-and-related-compounds/cat/279646">PCBs
                            & related compounds</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Environmental/Flame-retardants/cat/279647">Flame
                            retardants</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Environmental/Dyes-and-metabolites/cat/279649">Dyes
                            & metabolites</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Environmental/Dioxins-and-furans/cat/279650">Dioxins
                            & furans</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Environmental/Pharmaceutical-and-veterinary-compounds-and-metabolites/cat/279651">Pharma
                            & vet compounds & metabolites</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Environmental/Mycotoxins/cat/279653">Mycotoxins</a>
                          </li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Environmental/Additional-organic-reference-materials/cat/279644">Additional
                            organic reference materials</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Environmental/Polycyclic-aromatic-hydrocarbons-PAHs-/cat/279654">Polycyclic
                            aromatic hydrocarbons (PAHs)</a></li>
                        </ul>
                        <ul class="footer-navigation__subcategories-column">
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Environmental/Volatile-organic-compounds-VOCs-/cat/279655">Volatile
                            organic compounds (VOCs)</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Environmental/Hydrocarbons-and-petrochemicals/cat/279656">Hydrocarbons
                            & petrochemicals</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Environmental/Standards-for-environmental-regulatory-methods/cat/279657">Standards
                            for environmental regulatory methods</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Environmental/Aqueous-inorganic/cat/279663">Aqueous
                            inorganic</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Proficiency-Testing/Water-and-Environmental-Schemes/cat/280826">Environmental
                            proficiency testing</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Environmental/Physical-properties/cat/279674">Physical
                            properties</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Environmental/Pesticides-and-metabolites/cat/279696">Pesticides
                            & metabolites</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Environmental/Perfluoroalkylated-substances-PFAS-/cat/285186">Perfluoroalkylated
                            substances (PFAS)</a></li>
                        </ul>
                      </div>
                    </li>
                    <li class="footer-navigation__category"><a
                        href="https://www.lgcstandards.com/GB/en/cat/324175"
                        class="footer-navigation__category-name">Forensic & Toxicology</a>
                      <button class="footer-navigation__category-expand"></button>
                      <div class="footer-navigation__subcategories">
                        <ul class="footer-navigation__subcategories-column">
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/279798">New psychoactive
                            substances (NPS)</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/279811">Sports drugs and
                            steroids</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/279812">Ethanol and related
                            materials</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/324096">Cannabinoids</a>
                          </li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/279770">Smoking-related
                            substances</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/279768">Opiates and
                            opioids</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/279762">Amphetamines</a>
                          </li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/279764">Benzodiazepines</a>
                          </li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/279765">Cocaine and related
                            materials</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/279767">Hallucinogens</a>
                          </li>
                        </ul>
                        <ul class="footer-navigation__subcategories-column">
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/279766">GHB and related
                            materials</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/279763">Barbiturates</a>
                          </li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/324180">Pharmaceutical
                            Toxicology</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/279771">Z-drugs</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/324099">Drug metabolism</a>
                          </li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/324100">Enviromental
                            toxicology</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/324102">Food mutagens</a>
                          </li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/324101">Mycotoxins</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/cat/279831">Proficiency
                            testing</a></li>
                        </ul>
                      </div>
                    </li>
                    <li class="footer-navigation__category"><a
                        href="https://www.lgcstandards.com/GB/en/Industrials/cat/279495"
                        class="footer-navigation__category-name">Industrial</a>
                      <button class="footer-navigation__category-expand"></button>
                      <div class="footer-navigation__subcategories">
                        <ul class="footer-navigation__subcategories-column">
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Industrial/Petroleum-reference-materials/cat/279705">Petroleum
                            reference materials</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Industrial/Physical-property-analysis-standards/cat/341134">Physical
                            property analysis standards</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Industrial/Petroleum-reference-materials/Sulfur-Nitrogen-Chlorine/cat/279709">Sulfur,
                            Nitrogen & Chlorine</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Industrial/Petroleum-reference-materials/Metallo-organic-standards/cat/279708">Metallo-organic
                            standards</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Industrial/Petroleum-reference-materials/Matrix-oils-and-solvents/cat/279713">Matrix
                            oils & solvents</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Industrial/Petroleum-reference-materials/Biodiesel-standards/cat/279714">Biodiesel
                            standards</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Industrial/Aqueous-inorganic/cat/279715">Aqueous
                            inorganic</a></li>
                        </ul>
                        <ul class="footer-navigation__subcategories-column">
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Industrial/Metal-alloys/cat/279733">Metal
                            alloys</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Industrial/Metal-alloys/Aluminium-base/cat/279736">Aluminium
                            base</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Industrial/Process-materials-geological-cement-and-soils/cat/279744">Process
                            materials, geological, cement & soils</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Industrial/Process-materials-geological-cement-and-soils/XRF-monitor-glasses/cat/279750">XRF
                            monitor glasses</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Industrial/Laboratory-consumables/cat/279726">Laboratory
                            consumables</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Industrial/Equipment-for-sample-preparation/cat/279757">Equipment
                            for sample preparation</a></li>
                        </ul>
                      </div>
                    </li>
                    <li class="footer-navigation__category"><a
                        href="https://www.lgcstandards.com/GB/en/Proficiency-Testing/cat/244597"
                        class="footer-navigation__category-name">Proficiency Testing</a>
                      <button class="footer-navigation__category-expand"></button>
                      <div class="footer-navigation__subcategories">
                        <ul class="footer-navigation__subcategories-column">
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Proficiency-Testing/Food-and-feed-Schemes/cat/280775">Food
                            & Feed</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Proficiency-Testing/Beverage-Schemes/cat/280732">Beverage</a>
                          </li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Proficiency-Testing/Water-and-Environmental-Schemes/cat/280826">Water
                            & Environmental</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Proficiency-Testing/Consumer-safety-Schemes/cat/280762">Consumer
                            Safety</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Proficiency-Testing/Consumer-safety-Schemes/Pharmaceutical-PHARMASSURE-/cat/280766">Pharmaceutical</a>
                          </li>
                        </ul>
                        <ul class="footer-navigation__subcategories-column">
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Proficiency-Testing/Clinical-Schemes/cat/280743">Clinical</a>
                          </li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Proficiency-Testing/Forensics-Schemes/cat/280811">Forensic</a>
                          </li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Proficiency-Testing/Petroleum-Schemes/cat/280823">Petroleum</a>
                          </li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/Quality-Control-Materials/cat/282461">Quality
                            Control Materials</a></li>
                          <li class="footer-navigation__subcategory"><a
                              href="https://www.lgcstandards.com/GB/en/proficiency-testing/proficiencyFAQ">FAQs</a>
                          </li>
                        </ul>
                      </div>
                    </li>
                  </ul>
                </section>
                <section class="footer-navigation__section">
                  <h2 class="footer-navigation__heading">LGC Group
                    <button class="footer-navigation__mcat-expand"></button>
                  </h2>
                  <ul class="footer-navigation__external-links footer-navigation__mobile-mcat-data footer-navigation__mobile-mcat-data-hide">
                    <li class="footer-navigation__link footer-navigation__link-external"><a
                        href="https://www.lgcgroup.com" target='_blank' rel='noopener noreferrer'>LGC
                      Group</a></li>
                    <li class="footer-navigation__link footer-navigation__link-external"><a
                        href="https://www.lgcgroup.com/newsroom-and-blog/news-and-blog/" target='_blank'
                        rel='noopener noreferrer'>LGC Group News</a></li>
                    <li class="footer-navigation__link footer-navigation__link-external"><a
                        href="https://www.lgcgroup.com/careers" target='_blank' rel='noopener noreferrer'>LGC
                      Careers</a></li>
                    <li class="footer-navigation__link footer-navigation__link-external"><a
                        href="https://mainestandards.com/" target='_blank' rel='noopener noreferrer'>Maine
                      Standards</a></li>
                    <li class="footer-navigation__link footer-navigation__link-external"><a
                        href="https://www.seracare.com" target='_blank'
                        rel='noopener noreferrer'>SeraCare</a></li>
                    <li class="footer-navigation__link footer-navigation__link-external"><a
                        href="http://www.atcc.org/" target='_blank' rel='noopener noreferrer'>ATCC</a></li>
                    <li class="footer-navigation__link footer-navigation__link-external"><a
                        href="https://www.brcglobalstandards.com" target='_blank' rel='noopener noreferrer'>BRCGS</a>
                    </li>
                    <li class="footer-navigation__link footer-navigation__link-external"><a
                        href="https://www.informed-choice.org" target='_blank' rel='noopener noreferrer'>Informed
                      Choice</a></li>
                    <li class="footer-navigation__link footer-navigation__link-external"><a
                        href="https://www.informed-sport.com" target='_blank' rel='noopener noreferrer'>Informed
                      Sport</a></li>
                    <li class="footer-navigation__link footer-navigation__link-external"><a
                        href="https://www.trc-canada.com/" target='_blank' rel='noopener noreferrer'>TRC
                      Canada</a></li>
                  </ul>
                </section>
                <section class="footer-navigation__section">
                  <h2 class="footer-navigation__heading">Help & Support
                    <button class="footer-navigation__mcat-expand"></button>
                  </h2>
                  <ul class="footer-navigation__help-and-support-links footer-navigation__mobile-mcat-data footer-navigation__mobile-mcat-data-hide">
                    <li class="footer-navigation__link"><a href="https://www.lgcstandards.com/GB/en/contact-us">Customer
                      Services</a></li>
                    <li class="footer-navigation__link"><a href="https://www.lgcstandards.com/GB/en/contact-us">Contact
                      Us</a></li>
                    <li class="footer-navigation__link"><a
                        href="https://www.lgcstandards.com/GB/en/support/faq">FAQs</a></li>
                    <li class="footer-navigation__link"><a
                        href="https://www.lgcstandards.com/GB/en/contact-us#distributors">Distributors</a>
                    </li>
                    <li class="footer-navigation__link"><a
                        href="https://www.lgcstandards.com/GB/en/support/Frequentlyaskedquestions/Dispatch-Times-Shipping-Charges">Delivery</a>
                    </li>
                    <li class="footer-navigation__link"><a href="https://www.lgcstandards.com/GB/en/sitemap">Sitemap</a>
                    </li>
                    <li class="footer-navigation__link"><a
                        href="https://www.lgcstandards.com/GB/en/orderRequest">Request a custom
                      quotation</a></li>
                  </ul>
                </section>
              </div>
            </div>
          </div>
          <div class="footer-bottom-bar">
            <div class="footer-bottom-bar__content">
              <div class="footer-bottom-bar__logo-and-copyright"><a class="footer-bottom-bar__logo" href="index.html">
                <img class="footer-bottom-bar__logo-img" alt="LGC Standards"
                     src="/medias/sys_master/root/hfc/h3e/9739819122718/9739819122718.png"> </a>
                <div class="footer-bottom-bar__copyright">LGC Limited 2022. All rights reserved.<br>All trademarks
                  acknowledged.
                </div>
              </div>
              <ul class="footer-bottom-bar__policies">
                <li class="footer-bottom-bar__policy"><a
                    href="https://www.lgcstandards.com/GB/en/termsandConditions">Terms and Conditions</a></li>
                <li class="footer-bottom-bar__policy"><a href="https://www.lgcstandards.com/GB/en/privacyPolicy">Privacy
                  Notice</a></li>
                <li class="footer-bottom-bar__policy"><a href="https://www.lgcstandards.com/GB/en/privacyPolicy">Cookie
                  Policy</a></li>
              </ul>
              <ul class="footer-bottom-bar__cards">
                <li class="footer-bottom-bar__card_po"></li>
                <li class="footer-bottom-bar__card_visa"></li>
                <li class="footer-bottom-bar__card_master-card"></li>
                <li class="footer-bottom-bar__card_amex"></li>
              </ul>
            </div>
          </div>
        </footer>
      </template>
    </template>
  </br-page>
</template>

<script lang="ts">
import {Configuration, initialize} from '@bloomreach/spa-sdk';
import {Component, Vue, Watch} from 'nuxt-property-decorator';
import Menu from '~/components/BrMenu.vue';
import FreeText from '~/components/FreeText.vue';
import Banners from '~/components/BrBanners.vue';
import CookieConsent from '~/components/BrCookieConsent.vue';
import {buildConfiguration} from '~/utils/buildConfiguration';

@Component({
  components: { 'br-cookie-consent': CookieConsent },
  async asyncData(context) {
    const configuration = buildConfiguration(context.route.fullPath);

    const page = await initialize({
      ...configuration,
      visitor: context.nuxtState?.visitor,
      httpClient: context.$axios,
      request: context.req,
    });

    if (process.server) {
      context.beforeNuxtRender(({ nuxtState }) => {
        nuxtState.visitor = page.getVisitor();
      });
    }

    return { configuration, page };
  },

  data: () => ({
    mapping: {
      menu: Menu,
      FreeText,
      Banners
    },
  }),
})
export default class App extends Vue {
  configuration!: Configuration;

  beforeMount() {
    this.configuration.httpClient = this.$axios;
  }

  beforeUpdate() {
    this.configuration.httpClient = this.$axios;
  }

  @Watch('$route', { deep: true })
  navigate() {
    this.$set(this.configuration, 'path', this.$route.fullPath);
  }
}
</script>
