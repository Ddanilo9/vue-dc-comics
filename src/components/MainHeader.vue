<template>
    <header>
       <div class="container">
            <img :src="logo" alt="">
            <ul class="nav">
                <li v-for="(link, i) in links" :key="i" class="nav-link">
                    <a href="">{{link.text}}</a>
                </li>
            </ul>
       </div>
    </header>
</template>
  
<script>
    import logo from '../assets/dc-logo.png'

  export default {
      data() {
        return {
            logo: logo,
            links: [
            {
                text: 'Charachters',
                current: false
            },
            {
                text: 'comics',
                current: false
            },
            {
                text: 'movies',
                current: false
            },
            {
                text: 'tv',
                current: false
            },
            {
                text: 'games',
                current: false
            },
            {
                text: 'collectibles',
                current: false
            },
            {
                text: 'video',
                current: false
            },
            {
                text: 'fans',
                current: false
            },
            {
                text: 'news',
                current: false
            },
            {
                text: 'shop',
                current: false
            },
            ]
        }
      }
  }  
</script>
  

<style scoped lang="scss">
    
    .container{
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 10px 0 10px 0;

        img{
            aspect-ratio: 1/1;
            width: 70px;
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

                &:hover{
                    border-bottom: 3px solid #0282F9;
                    padding-bottom: 33px;
                }
            }

            &:hover{
                color: #0282F9;
            }
        }
    }
</style>