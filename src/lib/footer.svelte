<script>
</script>

<main>
  <footer>
    <div class="container">
      <div class="row">
        <div class="div-other-site col-lg-3 col-6">
          <h3>Otros Sitios</h3>
          <ul>
            <li>Portal de educacion</li>
            <li>Programa Papas</li>
            <li>Intranet</li>
            <li>Delphos</li>
            <!-- svelte-ignore a11y-missing-attribute -->
            <li><img src="/img/UnionEuropea.png" class="logo-azarquiel-imagen"/></li>
          </ul>
        </div>
        <div class="div-contact col-lg-3 col-6">
          <h3>Contacto</h3>
          <ul>
            <li>I.E.S Azarquiel</li>
            <li>Paseo de San Eugenio, 21</li>
            <li>45003 - Toledo</li>
            <li>923989379379</li>
            <li>desde el 20/10/2020 No operativo</li>
            <li>Centro: </li>
            <li>AMPA</li>
            <li>PAPAS</li>
          </ul>
        </div>
        <div class="div-locate col-lg-6 col-12">
          <h3>Localización </h3>
          <!-- svelte-ignore a11y-missing-attribute -->
          <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3062.1442480588576!2d-4.025167485179981!3d39.871006696572515!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xd6a0a53483a57e7%3A0xc7f7d4815179b44b!2sIES%20Azarquiel!5e0!3m2!1ses!2ses!4v1675194652934!5m2!1ses!2ses" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"/>
        </div>
      </div>
    </div>
  </footer>
</main>

<style lang="sass">

@mixin flexstyle()

iframe
  width: 33rem
  height: 13rem
footer
  width: 100%
  background-color: #009CDE 

main
  color: white

.div-other-site
  @include flexstyle()
.div-contact
  @include flexstyle()
.div-locate
  @include flexstyle()
  
ul
  padding: 0
ul li
  list-style: none
  margin: 0

img
  width: 15rem
@media screen and (max-width: 1090px)
  iframe
    width: 100%
    height: 13rem

@media screen and (max-width: 500px)
  .logo-azarquiel-imagen
    max-width: 100%
</style>
