<template>
  <q-page class="row justify-center"> 
    <div class="text-h2 text-weight-regular text-center absolute" align="center" style="margin-top:25px">ABOUT</div>
    <div class="q-pa-md row items-center justify-center q-gutter-md no-wrap" style="margin-top:35px" > 
      <q-card class="my-card">
        <img src="../assets/imagens/nseoultower.jpg">

        <q-card-section>
          <div class="text-h6">N Seoul Tower</div>
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
          <div class="text-h6">History</div>
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
          <div class="text-h6">Attractions</div>
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
       
      <div class="text-h2 text-weight-regular absolute-bottom" align="center" style="margin-top:40px">EXPLORE</div>
      <div class="q-pa-md row items-center justify-center q-gutter-md no-wrap">
        <q-card class="my-card">
      <img src="https://cdn.quasar.dev/img/mountains.jpg">

      <q-card-actions align="right">
        <q-btn flat round color="red" icon="favorite" />
        <q-btn flat round color="teal" icon="bookmark" />
        <q-btn flat round color="primary" icon="share" />
      </q-card-actions>
    </q-card>

    <q-card class="my-card">
      <img src="https://cdn.quasar.dev/img/mountains.jpg">

      <q-card-actions align="right">
        <q-btn flat round color="red" icon="favorite" />
        <q-btn flat round color="teal" icon="bookmark" />
        <q-btn flat round color="primary" icon="share" />
      </q-card-actions>
    </q-card>

    <q-card class="my-card">
      <img src="https://cdn.quasar.dev/img/mountains.jpg">

      <q-card-actions align="right">
        <q-btn flat round color="red" icon="favorite" />
        <q-btn flat round color="teal" icon="bookmark" />
        <q-btn flat round color="primary" icon="share" />
      </q-card-actions>
    </q-card>
    </div> 

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
  max-width: 230px
</style>