<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
export default {
  data() {
    return { 
      count: 0
    }
  },
  components: {
    AppTitle,
    AppHero
  },
  methods: {
    incrementCount() {
      this.count++;
    }
  }
}
</script>

<template>
  <div>
    <AppHero />
    <AppTitle />
    <main>
      <button @click="incrementCount()">
        {{ count }}
      </button>
    </main>
  </div>
</template>

<style scoped>
main {
  text-align: center;
}
</style>