<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated>
      <q-toolbar>
        <q-toolbar-title class="text-center">
          N Seoul Tower
        </q-toolbar-title>
      </q-toolbar>
    </q-header>
    <div class="q-pa-md"  >
    <q-carousel
      animated
      v-model="slide"
      navigation
      infinite
      :autoplay="autoplay"
      arrows
      transition-prev="slide-right"
      transition-next="slide-left"
      @mouseenter="autoplay = false"
      @mouseleave="autoplay = true"
    >
      <q-carousel-slide :name="1" img-src="../assets/imagens/foto01.jpg" />
      <q-carousel-slide :name="2" img-src="../assets/imagens/foto02.jpg" />
      <q-carousel-slide :name="3" img-src="../assets/imagens/foto03.jpg" />
      <q-carousel-slide :name="4" img-src="../assets/imagens/foto04.jpg" />
    </q-carousel>
  </div>
    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
  
</template>

<script>
import { defineComponent,ref} from 'vue'

export default defineComponent({
  name: 'MainLayout',

  setup () {
  
    return {
       slide: ref(1),
      autoplay: ref(true)

    }
  }
})
</script>


