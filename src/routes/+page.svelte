<script>

</script>

<main>
  <div class="cardcontainers">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 text-center">
          <div class="card">
            <h3>Curso en Especializacion de desarrollo de Videojuegos</h3>
            <a href="/desarrolloVideojuegos">
              <div class="go-corner">
                <div class="go-arrow">
                 <a href="/desarrolloVideojuegos"> <i class="fa-solid fa-location-arrow"></i></a>
                </div>
              </div> 
            </a>
          </div>
        </div>

        <div class="col-lg-6 text-center">
          <div class="card">
            <h3>Curso de Especializacion en ciberseguridad</h3>
           <a href="/Ciberseguridad">
            <div class="go-corner" href="#">
              <div class="go-arrow">
                <a href="/Ciberseguridad"><i class="fa-solid fa-location-arrow"></i></a>
              </div>
            </div> 
           </a>
          </div>
        </div>

      </div>
    </div>
  </div>
</main>

<style lang="sass">
.cardcontainers
  margin: 2rem 0 7rem 0
.card
  width: 75%
  height: 100%
  margin: 2rem 0
  z-index: 0
  overflow: hidden
  display: flex
  justify-content: center
  align-items: center
  &:before 
    content: ""
    position: absolute
    z-index: -1
    top: -50%
    right: -10%
    background: #009CDE 
    height: 32px
    width: 32px
    border-radius: 32px
    transform: scale(1)
    transform-origin: 50% 50%
    transition: transform 0.75s ease-out
  &:hover:before
    transform: scale(50)
  &:hover
    transition: all 0.75 ease-out
    box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px
    h3
      transition: all 0.75 ease-out
      color: white
    .go-corner
      transition: all 0.75 ease-out
      background-color: white
      box-shadow: rgb(38, 57, 77) 0px 20px 30px -10px
      &:hover
        box-shadow: rgba(0, 0, 0, 0.3) 0px 19px 38px, rgba(0, 0, 0, 0.22) 0px 15px 12px
        
      a
        color: #002973
        font-size: 1.2rem

.go-corner 
  display: flex
  align-items: center
  justify-content: center
  position: absolute
  width: 2.5rem
  height: 2.5rem
  overflow: hidden
  top: 0
  right: 0
  background-color: #009CDE 
  border-radius: 0 4px 0 32px

.go-arrow 
  margin-top: -4px
  margin-right: -4px
  color: white
  font-family: courier, sans

h3
  color: #009CDE 
  font-weight: bold 
a
  color: white
  &:hover i
   transform: scale(1.3,1.3)
@media screen and (max-width: 1000px)
  .col-lg-6
    margin: 2rem 0
  .card
    width: 100%
    height: 120%
  h3
    font-size: 0.75em

</style>