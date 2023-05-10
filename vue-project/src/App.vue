<template>
<div><nav-bar/>
<router-view></router-view>
</div>
</template>

<script>

import navBar from './components/navBar.vue'
export default {
components: {
  navBar,

}
}
</script>

<style>
</style>