<template>
  <div class="home">
    <div class="v-container">
      <Line />
      <div class="v-inner">
        <Card 
          v-for="item in 4" 
          :key="item" />
      </div>
    </div>
  </div>
</template>

<script>
import Line from '../components/Lines/v-line.vue'
import Card from '../components/UI/Card/v-card.vue'

export default {
  components: {
    Line,
    Card
  }
}
</script>
