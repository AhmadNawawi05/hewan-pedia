<template>
  <div>
    <NavbarComponent />
    <ContenComponent />
    <FooterComponent />
  </div>
</template>

<script > 
import 'flowbite/dist/flowbite.js'

import NavbarComponent from './components/NavbarComponent.vue';
import ContenComponent from './components/ContentComponent.vue';
import FooterComponent from './components/FooterComponent.vue';

export default {
  components: {
    NavbarComponent,
    ContenComponent,
    FooterComponent
  }
}

  // if (localStorage.getItem('color-theme') === 'dark' || (!('color-theme' in localStorage) && window.matchMedia('(prefers-color-scheme: dark)').matches)) {
  //       document.documentElement.classList.add('dark');
  //   } else {
  //       document.documentElement.classList.remove('dark')
  //   }
</script>