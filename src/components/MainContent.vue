<template>
  <main>
    <div class="main-up">
        <div class="container">
        <h1>-->CONTENT GOES HERE</h1>
      </div>
    </div>
    
    <div class="main-down">
      <div class="container">
        <ul class="menu">
          <li class="menu-links">
            <a href="">
              <img src="@/assets/buy-comics-digital-comics.png" alt="">
               Digital Comics</a>
          </li>
          <li class="menu-links">
            <a href="">
              <img src="@/assets/buy-comics-merchandise.png" alt="">
               Dc Merchandise</a>
          </li>
          <li class="menu-links">
            <a href="">
              <img src="@/assets/buy-comics-subscriptions.png" alt="">
               Subscription
              </a>
          </li>
          <li class="menu-links">
            <a href="">
              <img src="@/assets/buy-comics-shop-locator.png" alt="">
               Comic shop locator</a>
          </li>
          <li class="menu-links">
            <a href="">
              <img src="@/assets/buy-dc-power-visa.svg" alt="">
               Dc power visa</a>
          </li>
        </ul>
      </div>
    </div>
    
  </main>
</template>
  
<script>
  export default {
      
  }  
</script>
  

<style scoped lang="scss">
  main{
    color: white;
      .main-up{
        background-color: black;
        padding: 40px;
      }

      .main-down{
        background-color: #0282F9;
        height: 125px;
        display: flex;
        align-items: center;

          .menu{
            display: flex;
            justify-content: space-between;

              .menu-links{
                display: flex;
                align-items: center;
              
                &:nth-child(5)img{
                  width: 100px;
                }
                a{
                  display: flex;
                  align-items: center;

                    img{
                      max-width: 20%;
                      margin-right: 8px;
                    }
              }  }
          }
      }
  }
</style>