<template>
<!-- -->
<div class="app">
  <div class="Teste">
  <GlassCard class="glass-back" style="top:10px; left:60px;"></GlassCard>
  </div>
  <vue-particles
        color="#dedede"
        :particleOpacity="0.7"
        :particlesNumber="180"
        shapeType="circle"
        :particleSize="4"
        linesColor="#dedede"
        :linesWidth="1"
        :lineLinked="true"
        :lineOpacity="0.4"
        :linesDistance="150"
        :moveSpeed="3"
        :hoverEffect="true"
        hoverMode="grab"
        :clickEffect="true"
        clickMode="push"
      >
      </vue-particles>
</div>
<!-- -->
</template>

<script>

import GlassCard from "../components/GlassCard.vue";

export default {
  components:{
    'GlassCard':GlassCard
  }
  
}
</script>

<style lang="css">
.app{
  background: linear-gradient(191deg, rgba(5,17,78,1) 0%, rgb(68, 177, 122) 100%);
}

.Teste{
  display: inline-block;
}

h1{
  color:white;
  text-align: center;
  padding: 1rem;
}
</style>
