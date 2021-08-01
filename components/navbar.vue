<template>
    <div>
        <div class="parentDiv">
            <div class="nav">
                <ul>
                <NuxtLink to="/" class="nuxt">Home</NuxtLink>
                <NuxtLink to="/shop" class="nuxt">shop</NuxtLink>
                <NuxtLink to="/contact" class="nuxt">contact</NuxtLink>
            </ul>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        data(){
            return{
                name:'navbar'
            }
        }
        
    }
</script>

<style>


.parentDiv {
  position: absolute;
  width: 100%;
  background-color: black;
  color: white;
  text-align: center;
}

.nav {
  text-align: center;
  margin-top: 10px;
  padding: 15px;
}
ul{
    color: white;
    text-align: center;
}

ul li{
  display: inline-block;
  padding: 15px;
  text-align: center;
}
.nuxt{
    color: white;
    margin: 5px;
}
</style>