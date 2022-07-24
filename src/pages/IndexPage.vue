<template>
  <q-page class="row justify-center"> 
    <div class="text-h2 text-weight-regular text-center absolute" align="center" style="margin-top:60px">ABOUT</div>
    <div class="q-pa-md row justify-center q-gutter-md no-wrap" style="margin-top: 180px"> 
      <q-card class="my-card">
        <img src="../assets/imagens/nseoultower.jpg">

        <q-card-section>
          <div class="text-h6 text-center">N Seoul Tower</div>
          <div class="text-body2 text-weight-light text-justify" style="margin-top:5px">The N Seoul Tower officially called
          the CJ Seoul Tower and better known as 
          The Namsan Tower  or Seoul Tower, is a 
          communication and observation tower located
          on Mount Namsan in central  Seoul, 
          South Korea.</div>
        </q-card-section>
        <q-card-section class="q-pt-none">
        </q-card-section>  
      </q-card>

      <q-card class="my-card">
        <img src="../assets/imagens/nseoultower2.jpg">

        <q-card-section>
          <div class="text-h6 text-center">History</div>
          <div class="text-body2 text-weight-light text-justify" style="margin-top:5px">It marks the highest point in Seoul.
        Built between 1969 and 1975, at a cost of 
        approximately  $ 2.5 million, it was opened
        to the public in 1980. 
        It measures 236.7 meters above sea level.  
        It is also known as Namsan Tower or 
        Seoul Tower. </div>
        </q-card-section>
        <q-card-section class="q-pt-none"> 
        </q-card-section>
      </q-card>

      <q-card class="my-card">
        <img src="../assets/imagens/nseoultower3.jpg">

        <q-card-section>
          <div class="text-h6 text-center">Attractions</div>
          <div class="text-body2 text-weight-light text-justify" style="margin-top:5px">Many visitors use the cable car to reach the 
        mountain and then complete the walk to the
        tower. The tower has a gift shop and restaurants 
        on the ground floor. 
        Visitors can climb the tower for a fee. 
        Most of Seoul city can be seen from the top.</div>
        </q-card-section>
        <q-card-section class="q-pt-none"> 
        </q-card-section>
      </q-card>  
      </div> 
  </q-page>

  <q-page class="row justify-center">
    <div class="text-h2 text-weight-regular text-center absolute" align="center" style="margin-top:60px">EXPLORE</div>
    <div class="q-pa-md row items-center justify-center q-gutter-md no-wrap" style="margin-top:180px" > 
    <q-card class="my-card01">
      <img src="../assets/imagens/foto05.jpg">
      <q-card-section>
          <div class="text-h6 text-center">Love Locks</div>
          <div class="text-body2 text-weight-light text-justify" style="margin-top:5px">The Love Lock Bridge originated from tales about locking the padlocks and 
            throwing away the keys symbolizing eternal love. 
            But… the love locks do not limit to couples. 
            Families and friends lock their love for each other too!
            It is a cliche, yet it's romantic. 
            You can take pictures, chat, and enjoy the beautiful view of Seoul.
             </div>
        </q-card-section>

      <q-card-actions align="center">
        <q-btn flat round color="red-9" icon="favorite" />
        <q-btn flat round color="teal-3" icon="bookmark" />
        <q-btn flat round color="grey-10" icon="share" />
      </q-card-actions>
    </q-card>

    <q-card class="my-card01">
      <img src="../assets/imagens/teddybear.jpg">
      <q-card-section>
          <div class="text-h6 text-center">Teddy Bear Museum</div>
          <div class="text-body2 text-weight-light text-justify" style="margin-top:5px ">The museum in N Seoul Tower narrates with teddy bears the past, present, 
            and future of Seoul. There is a history gallery and a special gallery where a teddy bear is dressed as a king of Joseon Dynasty 
            and also shows a wide variety of early images of Seoul in the old days.</div>
        </q-card-section>

      <q-card-actions align="center">
        <q-btn flat round color="red-9" icon="favorite"/>
        <q-btn flat round color="teal-3" icon="bookmark" />
        <q-btn flat round color="grey-10" icon="share" />
      </q-card-actions>
    </q-card>

    <q-card class="my-card01">
      <img src="../assets/imagens/ngrill.jpg">
      <q-card-section>
          <div class="text-h6 text-center">N Grill French Restaurant</div>
          <div class="text-body2 text-weight-light text-justify" style="margin-top:5px ">High class French cuisine directly presented by n.Grill chef!
            n.Grill, a French restaurant, is located in the highest point of the N SEOUL TOWER
            boasting the best view.
            It should be unforgettable memories for you and your love.</div>
        </q-card-section>

      <q-card-actions align="center">
        <q-btn flat round color="red-9" icon="favorite" />
        <q-btn flat round color="teal-3" icon="bookmark" />
        <q-btn flat round color="grey-10" icon="share" />
      </q-card-actions>
    </q-card>
    </div>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'


export default defineComponent({
  name: 'IndexPage'
})


</script>

<style lang="sass" scoped>
.my-card
  width: 100%
  max-width: 300px
  height:400px
  margin-top:35px
</style>

<style lang="sass" scoped>
.my-card01
  width: 100%
  max-width: 300px
  height:530px
  margin-top:35px
</style>