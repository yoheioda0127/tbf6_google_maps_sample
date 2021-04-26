<template>
  <div id="app">
    <google-map/>
  </div>
</template>


<script>
  import axios from "axios";

  import $Scriptjs from "scriptjs"; 
  import GoogleMap from "./components/Map.vue"; 

  const API_KEY = "AIzaSyBfhcfqlsIYAkc9Cw77AjwOb7BkOM-f3G0";
  const API_URL = "https://maps.googleapis.com/maps/api/js?key=AIzaSyBfhcfqlsIYAkc9Cw77AjwOb7BkOM-f3G0&libraries=places";;
  
  export default {

  }
</script>

　
<style> 
  html,body {
    margin: 0;
    padding: 0;
  }
  #app {
    height: 100vh;
  }
</style>
