<template>
    <footer>
      <div class="upper-up">
      <div class="container footer-links">
        <div class="container-links">
          <h4>Dc Comics</h4>
          <ul>
            <li><a href=""></a>link</li>
            <li><a href=""></a>link</li>
            <li><a href=""></a>link</li>
            <li><a href=""></a>link</li>
            <li><a href=""></a>link</li>
            <li><a href=""></a>link</li>
            <li><a href=""></a>link</li>
          </ul>
          <h4>SHOP</h4>
          <ul>
            <li><a href=""></a>link</li>
            <li><a href=""></a>link</li>
          </ul>
        </div>
        <div class="container-links">
          <h4>DC</h4>
          <ul>
            <li><a href=""></a>link</li>
            <li><a href=""></a>link</li>
            <li><a href=""></a>link</li>
            <li><a href=""></a>link</li>
            <li><a href=""></a>link</li>
            <li><a href=""></a>link</li>
            <li><a href=""></a>link</li>
            <li><a href=""></a>link</li>
            <li><a href=""></a>link</li>
            <li><a href=""></a>link</li>
            <li><a href=""></a>link</li>
            <li><a href=""></a>link</li>
          </ul>
        </div>
        <div class="container-links">
          <h4>SITES</h4>
          <ul>
            <li><a href=""></a>link</li>
            <li><a href=""></a>link</li>
            <li><a href=""></a>link</li>
            <li><a href=""></a>link</li>
            <li><a href=""></a>link</li>
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
            <li><a href=""><img src="@/assets/footer-facebook.png" alt=""></a></li>
            <li><a href=""><img src="@/assets/footer-facebook.png" alt=""></a></li>
            <li><a href=""><img src="@/assets/footer-facebook.png" alt=""></a></li>
            <li><a href=""><img src="@/assets/footer-facebook.png" alt=""></a></li>
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
        padding: 30px 0 30px 0;
      }

      h4{
        margin-right: 20px;
        padding-bottom: 10px;
      }
  }
  .bottom-side{
    background-color:#303030;

      .contact-us{
      display: flex;
      justify-content: space-between;
      padding: 20px 0 20px 0;
        .socials{
          display: flex;
          align-items: center;
        }
          ul{
            display: flex;
            gap: 10px;
          }
  }
  }
  
</style>