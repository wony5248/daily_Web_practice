<template>
  <div id="app">
    <NavMenu></NavMenu>
    <router-view/>
  </div>
</template>

<script>
import NavMenu from "./components/NavMenu"
export default {
  components: { NavMenu },
  
}
</script>
<style>

</style>


