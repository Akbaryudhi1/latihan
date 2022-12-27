<template>
  <main>
    <HeroVue/>
  </main>
</template>
<script>
import { defineComponent,ref } from 'vue';
import HeroVue from '../components/Hero.vue';
export default defineComponent({
  components:{
    HeroVue
  },
  setup(){
    const angka = ref(0)
    const tambah = () => {
angka.value++
}
    return{
angka, tambah
    }
  }
})
</script>
<style scoped>
button{
  border: none;
  border-radius: 5px;
  background-color: aquamarine;
  color: #000;
  padding: .5rem 1rem;
}
</style>