<template>
 <div class="container">
   <NavbarComponenrtsView></NavbarComponenrtsView>
   <div class="Muzeum_input">
      <div class="Muzeum">
        Muzey <div class="museum_namber"><span>37</span></div>
      </div>
     <div class="muzeylar">
       Uzbekistan Rrespublikasidagi barcha muzeylar
     </div>
   </div>
   <div class="filter-bar">
     <div class="search-box">
       <i class="lupa">
         <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-search" viewBox="0 0 16 16">
           <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001q.044.06.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1 1 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0"/>
         </svg>
       </i>
       <input
         type="text"
         placeholder="Kalit so‘zlar bo‘yicha qidiruv"
       />
     </div>
     <select class="select-box">
       <option>Xudud</option>
       <option>Toshkent</option>
       <option>Samarqand</option>
     </select>
     <select class="select-box">
       <option>Rryting</option>
       <option>Yuqori</option>
       <option>Past</option>
     </select>
   </div>
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
