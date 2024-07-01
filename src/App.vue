<template>
  <div class="Wrapper">
    <navbar-comp/>
    <main>
      <router-view/>
    </main>
  
  </div>
</template>
<script>
import NavbarComp from '@/components/NavbarComp.vue'
export default{
components:{
  NavbarComp
}
}
</script>

<style></style>

