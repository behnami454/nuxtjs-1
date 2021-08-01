<template>

 <div class="asl">
        <div class="contact">
            this is home page
        </div>
        <div>
        
        </div>
 </div>
                   

    
</template>

<script>
import navbar from '../components/navbar.vue'
export default {
  data() {
    return {
      components: 
      navbar,
      
    };
  },
}
</script>
<style>
body{
  background-color: rgb(241, 235, 235);
}
.contact{
        padding: 20px;
        margin: 50px;
        border: 10px solid black;
    }
.asl{
        margin: 20px;
    }
i{
  color:black

    }
</style>
