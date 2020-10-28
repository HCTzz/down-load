<template>
  <div id="app">
    <down-load :on-refresh="onRefresh">
      <ul>
        <li>1</li>
        <li>1</li>
        <li>1</li>
        <li>1</li>
        <li>1</li>
        <li>1</li>
        <li>1</li>
        <li>1</li>
        <li>1</li>
        <li>1</li>
        <li>1</li>
        <li>1</li>
        <li>1</li>
        <li>1</li>
        <li>1</li>
        <li>1</li>
        <li>1</li>
        <li>1</li>
        <li>1</li>
        <li>1</li>
        <li>1</li>
        <li>1</li>
        <li>1</li>
        <li>1</li>
        <li>1</li>
        <li>1</li>
      </ul>
    </down-load>
  </div>
</template>

<script>
import downLoad from './lib/downLoad'
export default {
  name: 'app',
  components:{
    'down-load':downLoad
  },
  data() {
    return {
      onRefresh: null
    }
  },
  methods: {
    
  }
}
</script>

<style lang="scss">
#app{
  margin: 0px;
  padding: 0px;
  height: 100%;
  width:100%;
}
</style>
