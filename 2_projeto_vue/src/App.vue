<template>
  <div>
    <PrimeiroComponente />
    <p>O Dado de app é: {{ testando }}</p>
    <LifeCycle />
  </div>
</template>

<script>
import PrimeiroComponente from './components/PrimeiroComponente.vue'
import LifeCycle from './components/LifeCycle.vue'
export default {
  name: 'App',
  components: {
    PrimeiroComponente,
    LifeCycle
  },
  data () {
    return {
      testando: 'teste'
    }
  }
}
</script>
