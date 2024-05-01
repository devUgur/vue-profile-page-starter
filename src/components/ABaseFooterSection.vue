<template>

    
    <footer class="footer">
        <div class="container">
          <div class="footer-content">
            <div class="footer-logo">
              Logo
            </div>
            <div class="footer-links">
              <ul class="footer-menu">
                <li><a href="#"></a></li>
                <li><a href="#"></a></li>
                <li><a href="#"></a></li>
                <li><a href="#"></a></li>
              </ul>
            </div>
            <div class="footer-social">
              <ul class="social-icons">
                <li><a href="#"><i class="fab fa-facebook-f"></i></a></li>
                <li><a href="#"><i class="fab fa-twitter"></i></a></li>
                <li><a href="#"><i class="fab fa-instagram"></i></a></li>
                <li><a href="#"><i class="fab fa-linkedin-in"></i></a></li>
              </ul>
            </div>
          </div>
          <div class="footer-bottom">
            <p>&copy; 2023 Your Company. All rights reserved.</p>
          </div>
        </div>
      </footer>

    
    <div class="attribute">
        Create by 
        <a href="">
            Jay Ramoliya
        </a >
    </div>
</template>

<script setup lang="ts">

</script>

<style  scoped>
.footer {
    font-size: 18px;
    background-color: #333;
    color: #fff;
    padding: 30px 0;
    border-radius: 10px;
}
  
.container {
    width: 100%;
    margin: 0 auto;
    padding: 0 50px;
}
  
.footer-content {
    display: grid;
    grid-template-columns: 25% 50% 25%;
}

  
.footer-menu {
    list-style: none;
    padding: 0;
    margin: 0;
    text-align: center;
}
  
.footer-menu li {
    display: inline-block;
    margin-right: 20px;
}
  
.footer-menu li:last-child {
    margin-right: 0;
}
  
.footer-menu a {
    color: #fff;
    text-decoration: none;
}
  
.social-icons {
    list-style: none;
    padding: 0;
    margin: 0;
}
  
.social-icons li {
    display: inline-block;
    margin-right: 10px;
}
  
.social-icons li:last-child {
    margin-right: 0;
}
  
.social-icons a {
    color: #fff;
    text-decoration: none;
    font-size: 20px;
}
  
.footer-bottom {
    margin-top: 20px;
    text-align: center;
}
  
.footer-bottom p {
    margin: 0;
}
  
@media (max-width: 768px) {
    .footer-content {
        grid-template-columns: repeat(1, 1fr);
        row-gap: 20px;
    }
    .footer-menu{
        text-align: left;
    }
    .footer-menu li {
      display: block;
      margin-bottom: 10px;
    }
}
  
.attribute{
    position: absolute;
    bottom: 10px;
}
</style>