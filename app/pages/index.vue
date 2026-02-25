<template>
 <div class="container">
   <NavbarComponenrtsView></NavbarComponenrtsView>
   <div class="row">
     <div class="col-xl-3" v-for="(item,index) in 8" :key="index">
       <CardComponentsView></CardComponentsView>
     </div>
   </div>
   <FouterComponentsView></FouterComponentsView>
 </div>
</template>
<script setup lang="ts">
</script>
