<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
           <router-link :to="{name:'home'}">Go to Home</router-link>
              hello 
                  
            </div>
            <div class="col-md-4">
  <router-view></router-view>
        </div>
        </div>
        
                  

    </div>
</template>
  
<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>