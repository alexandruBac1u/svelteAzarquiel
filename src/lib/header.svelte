<script>

</script>

<main >
<section id="sp-top-bar">
  <div class="container header1">
    <div class="row">
      <div id="" class="col-lg-7">
        <div class="sp-column">
          <ul>
            <li>
              <a href="https://www.facebook.com/people/iesazarquiel/100088978323687/" ><i class="fa fa-facebook" /></a >
            </li>
            <li>
              <a href="http://twitter.com/iesazarquiel"><i class="fa fa-twitter" /></a >
            </li>
            <li>
              <a href="https://vimeo.com/user40137199"><i class="fa fa-youtube" /></a >
            </li>
            <li>
              <a href="https://www.flickr.com/photos/iesazarquiel/albums"><i class="fa fa-flickr"/></a>
            </li>
            <li>
              <a href="https://www.flickr.com/photos/195436459@N02/albums" ><i class="fa fa-flickr" /></a >
            </li>
            <li>
              <a href="https://www.instagram.com/iesazarquiel/"><i class="fa fa-instagram" /></a  >
            </li>
          </ul>
        </div>
      </div>
      <div class="col-lg-5">
        <div class="sp-column">
          <ul>
            <li>
              <i class="fa fa-phone"  />
              <a href="tel:925284043">925284043</a>
            </li>
            <li class="sp-contact-email">
              <i class="fa fa-envelope"/>
              <a href="mailto:45003875.ies@edu.jccm.es">45003875.ies@edu.jccm.es</a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</section>
<header>
  <div class="container header2">
    <div class="row">
      <div id="div1" class="col-4">
        <div class="logo-azarquiel">
          <!-- svelte-ignore a11y-missing-attribute -->
          <a href="/"><img src="/img/logo-azarquiel.png" class="logo-azarquiel-imagen"/></a>
        </div>
      </div>
      <div id="div2" class="col-8">
        <ul class="header2-ul1">
          <li class="mobile-hiden">INICIO</li>
          <li class="mobile-hiden"> AL DIA <i class="fa-solid fa-angle-down"></i></li>
          <li class="mobile-hiden">EL LORO</li>
          <li class="mobile-hiden">EL CENTRO <i class="fa-solid fa-angle-down"></i></li>
          <li class="mobile-hiden">SECRETARIA <i class="fa-solid fa-angle-down"></i></li>
          <li class="mobile-hiden">FAMILIAS <i class="fa-solid fa-angle-down"></i></li>
          <li class="mobile-hiden">BOLSA</li>
          <li>
            <i class="fa fa-bars btn btn-primary header2-bars" type="button" data-bs-toggle="offcanvas" data-bs-target="#demo"></i>
         </li>
        </ul>
      </div>
    </div>
  </div>
  
</header>
<div class="offcanvas offcanvas-end" id="demo">
    <div class="offcanvas-header search-header">
      <h1 class="offcanvas-title search-title">SEARCH <i class="fa-solid fa-xmark" data-bs-dismiss="offcanvas"></i></h1><br>
      <input type="email" class="form-control search-input" id="exampleInputEmail1" placeholder="SEARCH...">
    </div>
    <div class="offcanvas-body">
      <p><i class="fa-solid fa-angle-right"></i> INICIO</p>
      <p><i class="fa-solid fa-angle-right"></i> AL DIA</p>
      <p><i class="fa-solid fa-angle-right"></i> EL LORO</p>
      <p><i class="fa-solid fa-angle-right"></i> EL CENTRO</p>
      <p><i class="fa-solid fa-angle-right"></i> SECRETARIA</p>
      <p><i class="fa-solid fa-angle-right"></i> FAMILIAS</p>
      <p><i class="fa-solid fa-angle-right"></i> BOLSA</p>
    </div>
  </div>
</main>

<style lang="sass">
.search-header
  display: flex
  flex-direction: column
  align-items: flex-start

.search-title
  width: 100%
  display: flex
  align-items: center
  justify-content: space-between
.search-input
  width: 15rem
.logo-azarquiel-imagen
  max-width: 20rem
ul 
  display: flex
  column-gap: 1rem

ul li 
  list-style: none


ul > li a 
  color: #999999


ul> li a 
  color: blue
  text-decoration: none

#sp-top-bar 
  background-color: #f5f5f5

header
  box-shadow: rgba(50, 50, 93, 0.25) 0px 50px 100px -20px, rgba(0, 0, 0, 0.3) 0px 30px 60px -30px
  position: sticky
  top: 0px
.header1 
  padding-top: 15px

.header2
  padding-top: 15px
  padding-bottom: 15px 
  
.header2-bars
  background-color: transparent
  color: black
  border: none

#div2
  display: flex
  align-items: center
  padding-top: 0.4rem

.offcanvas
  background-color: black
  color: white

@media screen and (max-width: 1200px)
  .mobile-hiden
    display: none
  #div2
    display: flex
    justify-content: end
@media screen and (max-width: 992px)
  .sp-column
    display: flex
    justify-content: center

@media screen and (max-width: 400px)
  .logo-azarquiel-imagen
    max-width: 200%
  a
    font-size: 0.75rem
</style>