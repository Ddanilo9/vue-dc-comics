<template>
    <header>
       <div class="container">
            <img src="@/assets/dc-logo.png" alt="">
            <ul class="nav">
                <li class="nav-link">
                    <a href="">Charachters</a>
                </li>
                <li class="nav-link">
                    <a href="">Comics</a>
                </li>
                <li class="nav-link">
                    <a href="">Movies</a>
                </li>
                <li class="nav-link">
                    <a href="">Tv</a>
                </li>
                <li class="nav-link">
                    <a href="">Games</a>
                </li>
                <li class="nav-link">
                    <a href="">Collectibles</a>
                </li>
                <li class="nav-link">
                    <a href="">Videos</a>
                </li>
                <li class="nav-link">
                    <a href="">Fans</a>
                </li>
                <li class="nav-link">
                    <a href="">News</a>
                </li>
                <li class="nav-link">
                    <a href="">Shop</a>
                </li>
            </ul>
       </div>
    </header>
</template>
  
<script>
  export default {
      
  }  
</script>
  

<style scoped lang="scss">
    
    .container{
        display: flex;
        justify-content: space-between;
        align-items: center;

        img{
            aspect-ratio: 1/1;
        }
    }

    .nav{
        display: flex;
        gap: 1rem;

        .nav-link{
            
            a{
                text-transform: uppercase;
                font-size: 14px;
                font-weight: 500;
            }

            &:hover{
                color: #0282F9;
            }
        }
    }
</style>