<template>


  <!-- contianer boshlandi -->
  <div class="container-fluid">
    <HeaderRow/>
<!--    main qatori boshladi-->
    <div class="row mt-4">
      <CategoriesCol/>
<!--  kontent boshlandi-->
      <div class="col-12 col-md-9 mt-4 mt-md-0">
       <router-view/>
      </div>
      <!--  kontent boshlandi-->
    </div>

    <!--    main qatori tugadi-->
   <FooterRow/>

  </div>
  <!-- contianer tugadi -->

</template>

<style scoped>

</style>

<script setup>
import HeaderRow from "./components/HeaderRow.vue";
import CategoriesCol from "./components/CategoriesCol.vue";
import FooterRow from "./components/FooterRow.vue";
import HomePage from "./views/HomePage.vue";

</script>