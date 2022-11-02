<script setup>
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <main>
    <SaraVue />
    <TheWelcome />
  </main>
</template>

<script >
import SaraVue from '../components/Sara.vue';

export default {
    name: 'Home',
    components:{
        SaraVue
    }
}
</script>
