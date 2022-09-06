<template>
   
    <div class="cards">
        <img :src="src" :alt="titolo">
        <h4>{{titolo}}</h4>
    </div>
</template>
    
    
  <script>
    export default {
        props: {
            src: String,
            titolo: String
        }
    }  
  </script>
    
  

<style scoped lang="scss">
    .cards{
        padding: 10px;
        cursor: pointer;
        
        img{
            aspect-ratio: 1/1;
        }

        h4{
            font-size: 12px;
            font-weight: 300;
        }
    }
</style>