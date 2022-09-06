<template>
  <main>
    <div class="main-up">
      <div class="jumbo">
      </div>
      <div class="container box-cards">
        <CardsComp v-for="(card,i) in cards" :key="i" :titolo="card.series" :src="card.thumb"></CardsComp>
      </div>
      <div class="button"><button>Load More</button>
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
import CardsComp from '@/components/CardsComp.vue'

  export default {
    components: {
      CardsComp,
    },
      data() {
        return {
          cards:
          [
            {
              "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
              "price": "$19.99",
              "series": "Action Comics",
              "type": "comic book"
            },
            {
              "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
              "price": "$3.99",
              "series": "American Vampire 1976",
              "type": "comic book"
            },
            {
              "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
              "price": "$16.99",
              "series": "Aquaman",
              "type": "graphic novel"
            },
            {
              "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
              "price": "$2.99",
              "series": "Batgirl",
              "type": "comic book"
            },
            {
              "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
              "price": "$3.99",
              "series": "Batman",
              "type": "comic book"
            },
            {
              "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
              "price": "$2.99",
              "series": "Batman Beyond",
              "type": "comic book"
            },
            {
              "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
              "price": "$3.99",
              "series": "Batman/Superman",
              "type": "comic book"
            },
            {
              "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
              "price": "$4.99",
              "series": "Batman/Superman Annual",
              "type": "comic book"
            },
            {
              "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
              "price": "$5.99",
              "series": "Batman: The Joker War Zone",
              "type": "comic book"
            },
            {
              "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
              "price": "$6.99",
              "series": "Batman: Three Jokers",
              "type": "comic book"
            },
            {
              "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
              "price": "$4.99",
              "series": "Batman: White Knight Presents: Harley Quinn",
              "type": "comic book"
            },
            {
              "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
              "price": "$16.99",
              "series": "Catwoman",
              "type": "graphic novel"
            }
          ]
        }
      },
      mounted(){
        console.log(this.cards)
      }
  }  
</script>
  

<style scoped lang="scss">
  main{
    color: white;
      .main-up{
        background-color: black;

        .jumbo{
          background-image: url(@/assets/jumbotron.jpg);
          height: 280px;
          background-size: cover;
          background-repeat: no-repeat;
        }
        .box-cards{
          display: grid;
          grid-template-columns: repeat(6, 1fr);
          grid-column-gap: 10px;
          grid-row-gap: 10px;
        }
        .button{
              display: flex;
              justify-content: center;
              padding: 10px;

              button{
                background-color: #0282F9;
                padding: 10px;
                color: white;
                text-transform: uppercase;
                cursor: pointer;
                width: 160px;
              }
            }
            
        

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
                }
              }
          }
      }
  }
</style>