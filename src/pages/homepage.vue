<template>
   <q-page>
      <div class="row">
         <div class="col-xs-12">
            <q-parallax class="parralax-top" :speed="0.5" src="~assets/vickyetpatrick001.jpg">
               <template v-slot:media>
                  <img src="~assets/vickyetpatrick001.jpg" class="img-bw img-top" />
               </template>

               <!-- <template v-slot:content="scope">
                  <div class="absolute column" :style="{ top: scope.percentScrolled * 165 + '%', marginTop: '-650px', left: 0, right: 0 }">
                     <div class="container">
                        <div class="text-h2 text-uppercase text-white">Vicky & Patrick</div>
                        <div class="text-h4 text-white">2.7.22</div>
                     </div>
                  </div>
               </template> -->
            </q-parallax>
         </div>
      </div>
      <div class="row bg-grey-3 custom-section">
         <div class="col-xs-12">
            <div class="container">
               <div class="text-center fleur-enveloppe"><q-img src="~assets/fleur_enveloppe.png" ratio="1" /></div>
               <p class="text-h1 text-center q-mb-xl">Vicky & Patrick</p>
               <p class="text-body1">
                  Nous nous sommes rencontré lors d'une promenade en fin d'été. Ce qui devait être une simple rencontre se transforma rapidement en
                  une véritable histoire d'amour. Et cette histoire continuera de s'écrire cet été puisque nous nous marierons devant Dieu ainsi que
                  les personnes que nous aimons.
               </p>
               <p class="text-body1">
                  Nous sommes heureux de vous inviter à notre union et de célébrer avec vous cette amour qui continue de grandir à chaque jour. Si
                  vous avez reçu notre faire-part pour la cérémonie et le souper, nous vous invitons à remplir le formulaire de confirmation en
                  cliquant sur le bouton ci-dessous.
               </p>
               <div class="text-center q-ma-xl">
                  <q-btn
                     href="https://forms.gle/YGD4jA9h5CA7uKf4A"
                     target="_blank"
                     color="secondary"
                     outline
                     unelevated
                     padding="20px 40px"
                     size="xl"
                     label="Confirmer votre présence"
                  />
               </div>
            </div>
         </div>
      </div>
      <div class="row bg-white custom-section">
         <div class="col-xs-12">
            <div class="container">
               <p class="text-h2 text-center q-mb-xl">Horaire de la journée</p>
               <div class="row">
                  <div class="col-xs-12 col-sm-1 col-md-2 col-lg-3"></div>
                  <div class="col-xs-12 col-sm-10 col-md-8 col-lg-6">
                     <q-list class="horaire">
                        <q-item>
                           <q-item-section avatar class="q-mr-lg heure">16h30</q-item-section>
                           <q-item-section>
                              <q-item-label class="text-body2">Cérémonie</q-item-label>
                           </q-item-section>
                        </q-item>

                        <q-item>
                           <q-item-section avatar class="q-mr-lg heure">17h30</q-item-section>
                           <q-item-section>
                              <q-item-label class="text-body2">Cocktail</q-item-label>
                           </q-item-section>
                        </q-item>

                        <q-item>
                           <q-item-section avatar class="q-mr-lg heure">18h00</q-item-section>
                           <q-item-section>
                              <q-item-label class="text-body2">Buffet dînatoire</q-item-label>
                           </q-item-section>
                        </q-item>

                        <q-item>
                           <q-item-section avatar class="q-mr-lg heure">19h30</q-item-section>
                           <q-item-section>
                              <q-item-label class="text-body2">Présentation des mariés</q-item-label>
                           </q-item-section>
                        </q-item>

                        <q-item>
                           <q-item-section avatar class="q-mr-lg heure">20h00</q-item-section>
                           <q-item-section>
                              <q-item-label class="text-body2">Début de la soirée dansante</q-item-label>
                           </q-item-section>
                        </q-item>
                     </q-list>
                  </div>
                  <div class="col-xs-12 col-sm-1 col-md-2 col-lg-3"></div>
               </div>

               <div class="text-center fleur-bottom"><q-img src="~assets/fleur_bottom.png" /></div>
            </div>
         </div>
      </div>
      <div class="row bg-grey-9 custom-section">
         <div class="col-xs-12">
            <div class="container">
               <p class="text-h2 text-center text-grey-2 q-mb-xl">Invitation à la soirée</p>
               <p class="text-body1 text-grey-3">
                  Pour nous, il est impossible de ne pas passer la soirée avec vous. Ce serait donc un honneur pour nous que vous nous rejoignez à
                  notre soirée pour danser et célébrer notre amour.
               </p>
               <p class="text-body1 text-grey-3">
                  Nous vous prions, de remplir le formulaire de confirmation à la soirée en cliquant sur le bouton ci-dessous.
               </p>
               <div class="text-center q-ma-xl">
                  <q-btn
                     href="https://forms.gle/7wGpPS7pSdWSDsVe8"
                     target="_blank"
                     color="white"
                     outline
                     unelevated
                     padding="20px 40px"
                     size="xl"
                     label="Confirmer votre présence à la soirée"
                  />
               </div>
            </div>
         </div>
      </div>

      <div class="row bg-grey-3 custom-section">
         <div class="col-xs-12">
            <div class="container">
               <p class="text-h2 text-center">Menu</p>
               <p class="text-body1 text-center" style="text-align: center">- Information à venir -</p>
               <p class="text-body1 text-center q-mt-lg" style="font-weight: 600">À propos de l'alcool</p>
               <p class="text-body1 text-italic text-center">
                  Nous vous offrons du vin blanc et du vin rouge pour le souper. Néanmoins, libre à vous d'apporter votre boisson.
               </p>
            </div>
         </div>
      </div>

      <div class="row bg-black custom-section">
         <div class="col-xs-12 q-pb-md">
            <div class="container">
               <p class="text-h2 text-white text-center">Endroit</p>
               <p class="text-body1 text-grey-4 text-center">2160, chemin du Lac, St-Félicien, G8K 3E5</p>
            </div>
         </div>
         <a href="#" target="_blank" style="display: block; width: 100%; height: 400px"
            ><q-img src="~assets/carte.png" fit="none" height="400px"
         /></a>
      </div>
   </q-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
   name: 'PageHomepage',
   setup() {
      return {}
   }
})
</script>

<style lang="scss">
// $

.custom-section {
   padding-top: 90px;
   padding-bottom: 60px;
}
.img-full-width {
   // width: 100%;
   // height: 100%;
}
.img-bw {
   filter: grayscale(100%);
}
.img-bw::before {
   background: rgba(255, 0, 30, 0.3);
}
.fleur-enveloppe {
   padding: 32px;
   margin-top: -64px;
   .q-img {
      width: 150px;
   }
}
.fleur-bottom {
   padding: 32px;
   .q-img {
      width: 350px;
   }
}
.horaire {
   font-size: 22px;
}
.heure {
   font-size: 22px;
}

body.screen--xs {
   font-size: 14px;

   .horaire {
      font-size: 16px;
   }
   .heure {
      font-size: 18px;
   }

   .container {
      padding-right: 32px;
      padding-left: 32px;
   }

   .q-ma-xl {
      margin-right: 0px;
      margin-left: 0px;
   }

   p {
      text-align: justify;
      &.text-center {
         text-align: center !important;
      }
   }

   .q-btn {
      width: 100% !important;
      font-size: 16px !important;
      padding-right: 16px;
      padding-left: 16px;
   }

   .text-h1 {
      font-size: 7em;
      margin-bottom: 16px !important;
   }
   .text-h2 {
      text-align: center;
      font-size: 6em;
      margin-bottom: 16px !important;
   }
   .fleur-enveloppe {
      padding: 0px;
      margin-top: -16px;
      .q-img {
         width: 90px;
      }
   }
   .fleur-bottom {
      margin-top: 32px;
      padding: 0;
      .q-img {
         width: 308px !important;
         height: 160px !important;
      }
   }
   .parralax-top {
      height: 300px !important;
   }
   .img-top {
      top: -500px;
      left: 50px;
      height: 600px;
   }
   .custom-section {
      padding-bottom: 30px;
      padding-top: 50px;
   }
}

body.screen--sm {
   .parralax-top {
      height: 300px !important;
   }
   .img-top {
      right: 100px !important;
      top: -500px;
      height: 600px;
   }
}

body.screen--md {
   .parralax-top {
      height: 450px !important;
   }
   .img-top {
      right: 100px;
      top: -500px;
      height: 800px;
   }
}

body.screen--lg {
   .parralax-top {
      height: 650px !important;
   }
   .img-top {
      top: -500px;
      height: 1000px;
   }
}

body.screen--xl {
   .parralax-top {
      height: 700px !important;
   }
   .img-top {
      height: 1200px;
   }
}
</style>
