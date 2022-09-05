<template>
    <footer>
      <div class="upper-up">
      <div class="container footer-links">
        <div class="container-links">
          <h4>Dc Comics</h4>
          <ul>
            <li><a href="">Charachters</a></li>
            <li><a href="">Comics</a></li>
            <li><a href="">Movies</a></li>
            <li><a href="">TV</a></li>
            <li><a href="">Games</a></li>
            <li><a href="">Movies</a></li>
            <li><a href="">News</a></li>
          </ul>
          <h4>SHOP</h4>
          <ul>
            <li><a href="">Shop DC</a></li>
            <li><a href="">Shop DC Collectables</a></li>
          </ul>
        </div>
        <div class="container-links">
          <h4>DC</h4>
          <ul>
            <li><a href="">Terms of use</a></li>
            <li><a href="">Privacy Policies</a></li>
            <li><a href="">Ad choises</a></li>
            <li><a href="">Advertising</a></li>
            <li><a href="">Jobs</a></li>
            <li><a href="">Subscriptions</a></li>
            <li><a href="">Talent Workshops</a></li>
            <li><a href="">CPSC Certificates</a></li>
            <li><a href="">Ratings</a></li>
            <li><a href="">Shop helps</a></li>
            <li><a href="">Contact Us</a></li>
          </ul>
        </div>
        <div class="container-links">
          <h4>SITES</h4>
          <ul>
            <li><a href="">DC</a></li>
            <li><a href="">MAD Magazine</a></li>
            <li><a href="">DC kids</a></li>
            <li><a href="">DC Universe</a></li>
            <li><a href="">Dc Power Visa</a></li>
          </ul>
        </div>
      </div>
    </div>
    <div class="bottom-side">
      <div class="container contact-us">
        <button>Sign up now</button>
        <div class="socials">
          <h4>Follow Us</h4>
          <ul>
            <li><a href=""><img src="@/assets/footer-facebook.png" alt=""></a></li>
            <li><a href=""><img src="@/assets/footer-twitter.png" alt=""></a></li>
            <li><a href=""><img src="@/assets/footer-youtube.png" alt=""></a></li>
            <li><a href=""><img src="@/assets/footer-pinterest.png" alt=""></a></li>
            <li><a href=""><img src="@/assets/footer-periscope.png" alt=""></a></li>
          </ul>
        </div>
      </div>
    </div>
    </footer>
</template>
  
<script>
  export default {
      
  }  
</script>
  

<style scoped lang="scss">
  .upper-up{
    background-image: url(@/assets/footer-bg.jpg);
    color: white;
  }
  .footer-links{
    display: flex;
    background-image: url(@/assets/dc-logo-bg.png);
    background-position: right;
    background-size: auto;
    background-repeat: no-repeat;

      .container-links{
        padding: 35px 0 35px 0;
        
        ul{
          color: #6E6E6E;
          margin-right: 20px;
          margin-bottom: 10px;
        }
      }

      h4{
        padding-bottom: 10px;
      }
  }
  .bottom-side{
    background-color:#303030;

      .contact-us{
      display: flex;
      justify-content: space-between;
      padding: 20px 0 20px 0;

        button{
          border: 2px solid #0282F9;
          background-color: transparent;
          padding: 5px;
          color: white;
          text-transform: uppercase;
          cursor: pointer;
          font-weight: 600;
        }
        .socials{
          display: flex;
          align-items: center;

            h4{
              color: #0282F9;
              margin-right: 20px;
            }
        }
          ul{
            display: flex;
            gap: 10px;
          }
  }
  }
  
</style>