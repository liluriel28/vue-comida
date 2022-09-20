<template>
  <div>
    <header>
      <nav>
          <ul>
            <li><a href="">Bebidas</a></li>
            <li><a href="">Hamburguesas</a></li>
            <li><a href="">Tacos</a></li>
            <li><a href="#">Uriel Marquez Cruz</a></li>
          </ul>
        </nav>
    </header>
  </div>

  <div>
    <h1>COMIDA RAPIDA</h1>
    <hr>
  </div>
  <div class="container">
    <card url="https://i.pinimg.com/originals/ef/4a/4a/ef4a4a551b83ee26dbfe2bafe3e34699.png" nombre="Hamburguesas" descripcion="Antes de que te despidas y decidas dejar todo esto en la nada" precio="$542.00"/>
    <card url="https://assets.stickpng.com/images/580b57fcd9996e24bc43c1b7.png" nombre="Hot Dogs" descripcion="Antes que finjas amarme y luego me digas que lo nuestro no es nada" precio="$630.00" />
    <card url="https://assets.stickpng.com/images/585abfc54f6ae202fedf2935.png" nombre="Papas" descripcion="Te voy a decir que lo hago solo para ver como brilla esa mirada" precio="$125.26"/>
    <card url="https://cdn.pixabay.com/photo/2019/05/16/16/42/pie-4207496_1280.png" nombre="Empanada" descripcion="Pero da igual, Pero da igual Hey babe, hey babe" precio="$426.35"/>
    <card url="https://www.pngplay.com/wp-content/uploads/2/Top-View-Pizza-PNG-HD-Quality.png" nombre="Pizza" descripcion="Tu aroma está matándome Tu mente está matándome" precio="$480.32"/>
    <card url="https://pngimg.com/uploads/spaghetti/spaghetti_PNG24.png" nombre="Espaguetti" descripcion="Tu tiempo está matándome
    Hey babe, hey babe" precio="$Gratis"/>
    
  </div>

  <div>
    <!-- Site footer -->
    <footer class="site-footer">
      <div class="container">
        <div class="row">
          <div class="col-sm-12 col-md-6">
            <h6>About</h6>
            <p class="text-justify">Mi identidad en el bar
              <p>No me acuerdo el lugar</p>
              <p>No lo veo del todo claro igual voy a llegar</p>
              <p>Mi alma pide paz, no sé dónde estará</p>
              <p>La calle me habla y yo como siempre voy a escuchar</p>
              
              </p>
          </div>

          <div class="col-xs-6 col-md-3">
            <h6>Categories</h6>
            <ul class="footer-links">
              <li><a href="https://open.spotify.com/track/6164L7BlwuEwS79l7DSCba?si=8576295d7a274443" target="_blank">C.R.O - SANGRE</a></li>
              <li><a href="https://open.spotify.com/track/5j0jbA5BKtx5KygkpoRt1S?si=f43e0b1bfebf45e1" target="_blank">C.R.O - GLORIA</a></li>
              <li><a href="https://open.spotify.com/track/5F9jYHqQdA5SNFTfIamzfJ?si=fc2ca38a4cf54518">C.R.O - POR LA CARRETERA</a></li>
              <li><a href="https://open.spotify.com/track/5DgU47dX4aCfPagjMqUqg8?si=7c3e0d4b83c54d22" target="_blank">C.R.O - ERROR</a></li>
              <li><a href="https://open.spotify.com/track/2DOlYD1QGUFYvaqTXFvB79?si=f8b2f3b123864303" target="_blank">C.R.O - MAL DE LA CABEZA</a></li>
            </ul>
          </div>

          <div class="col-xs-6 col-md-3">
            <h6>Quick Links</h6>
            <ul class="footer-links">
              <li><a href="#">About Us</a></li>
              <li><a href="#">Contact Us</a></li>
              <li><a href="#">Contribute</a></li>
              <li><a href="#">Privacy Policy</a></li>
              
            </ul>
          </div>
        </div>
        <hr>
      </div>
      <div class="container">
        <div class="row">
          <div class="col-md-8 col-sm-6 col-xs-12">
            <p class="copyright-text">Copyright &copy; 2017 All Rights Reserved by 
         <a href="https://www.facebook.com/uriel.marquez.90475" target="_blank">UrielMc</a>.
            </p>
          </div>

          
        </div>
      </div>
</footer>
  </div>
</template>

<style>
  
  nav{
    float: center; /* Desplazamos el nav hacia la izquierda */
    background-color: black;
  }

  nav ul {
    list-style: none;
    overflow: hidden; /* Limpiamos errores de float */
  }

  nav ul li {
    float: left;
    font-family: Arial, sans-serif;
    font-size: 16px;
  }

  nav ul li a {
    display: block; /* Convertimos los elementos a en elementos bloque para manipular el padding */
    padding: 20px;
    color: rgb(255, 255, 255);
    text-decoration: none;
  }

  nav ul li:hover {
    background: #FFAC41;
  }

  h1{
    text-align: center;
  }
  
 /*------Footer ------------*/
  .site-footer
  {
    background-color:#000000;
    padding:45px 0 20px;
    font-size:15px;
    line-height:24px;
    color:#ffffff;
  }
  .site-footer hr
  {
    border-top-color:#bbb;
    opacity:0.5
  }
  .site-footer hr.small
  {
    margin:20px 0
  }
  .site-footer h6
  {
    color:#fff;
    font-size:16px;
    text-transform:uppercase;
    margin-top:5px;
    letter-spacing:2px
  }
  .site-footer a
  {
    color:#ffffff;
  }
  .site-footer a:hover
  {
    color:#fff200;
    text-decoration:none;
  }
  .footer-links
  {
    padding-left:0;
    list-style:none
  }
  .footer-links li
  {
    display:block
  }
  .footer-links a
  {
    color:#737373
  }
  .footer-links a:active,.footer-links a:focus,.footer-links a:hover
  {
    color:#fff700;
    text-decoration:none;
  }
  .footer-links.inline li
  {
    display:inline-block
  }
  
  .copyright-text
  {
    margin:0
  }
  @media (max-width:991px)
  {
    .site-footer [class^=col-]
    {
      margin-bottom:30px
    }
  }
  @media (max-width:767px)
  {
    .site-footer
    {
      padding-bottom:0
    }
    .site-footer .copyright-text,.site-footer .social-icons
    {
      text-align:center
    }
  }
  .social-icons
  {
    padding-left:0;
    margin-bottom:0;
    list-style:none
  }
  .social-icons li
  {
    display:inline-block;
    margin-bottom:4px
  }
  .social-icons li.title
  {
    margin-right:15px;
    text-transform:uppercase;
    color:#96a2b2;
    font-weight:700;
    font-size:13px
  }
  .social-icons a{
    background-color:#eceeef;
    color:#818a91;
    font-size:16px;
    display:inline-block;
    line-height:44px;
    width:44px;
    height:44px;
    text-align:center;
    margin-right:8px;
    border-radius:100%;
    -webkit-transition:all .2s linear;
    -o-transition:all .2s linear;
    transition:all .2s linear
  }
  .social-icons a:active,.social-icons a:focus,.social-icons a:hover
  {
    color:#fff;
    background-color:#f2ff00
  }
  .social-icons.size-sm a
  {
    line-height:34px;
    height:34px;
    width:34px;
    font-size:14px
  }
  
  @media (max-width:767px)
  {
    .social-icons li.title
    {
      display:block;
      margin-right:0;
      font-weight:600
    }
  }

</style>

<script>
  import Card from "./componets/Card.vue"
  
  export default {
    components:{
      Card,
    },
  };
</script>