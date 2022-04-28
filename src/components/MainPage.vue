<template>
  <div>
      <main-navbar />
      <div class="mt-2 text-start mx-4 row">
        <div class="col-md"><h3>Science Focus</h3></div>

        <div class="col-md">
           <form action="">
            <div class="input-group mb-3">
              <input type="text" class="form-control " placeholder="Enter Your Search" name='search-text'>
              <span class="input-group-text">Search</span>
            </div>
          </form>
        </div>
      </div>
      <main-navbar-2 />

      <div class="bg-dark text-start text-white">
        <footer>
         <span>made by:rahim einollahi</span>
         <address>go to rahim.einollahi1 instagram</address>
        </footer>
      </div>
         
  </div>
</template>

<script> 
  import MainNavbar from './MainNavbar.vue'
  import MainNavbar2 from './MainNavbar2.vue'
  export default {
    name:"MainPage",
    components:{
      MainNavbar,
      MainNavbar2
    }
  }
</script>

<style lang="scss" scoped>

</style>