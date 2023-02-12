<script>

</script>

<main>
  <div class="portada">
    <p>Curso en Especializacion de desarrollo de Videojuegos</p>
  </div>
  <div class="contenedorinfo">
    
    <div class="container">
      <button data-bs-toggle="collapse" data-bs-target="#demo1" class="row"><div class="col-10">¿Quien puede acceder a estas enseñanzas?</div> <div class="col-2 text-end"><i class="fa-solid fa-angle-down"></i></div></button>
        
      <div id="demo1" class="collapse">
        <div class="contdiv">
          <ul>
            <li>&nbsp; Técnico Superior en Administración de Sistemas Informáticos en Red establecido por
              el Real Decreto 1629/2009, de 30 de octubre, por el que se establece el título de
              Técnico Superior en Administración de Sistemas Informáticos en Red y se fijan sus
              enseñanzas mínimas</li>
            <li>&nbsp; Técnico Superior en Desarrollo de Aplicaciones Multiplataforma, establecido por el
              Real Decreto 450/2010, de 16 de abril, por el que se establece el título de Técnico
              Superior en Desarrollo de Aplicaciones Multiplataforma y se fijan sus enseñanzas
              mínimas</li>
            <li>&nbsp; Técnico Superior en Desarrollo de Aplicaciones Web, establecido por el Real Decreto
              686/2010, de 20 de mayo, por el que se establece el título de Técnico Superior en
              Desarrollo de Aplicaciones Web y se fijan sus enseñanzas mínimas</li>
            <li>&nbsp; Técnico Superior en Animaciones 3D, Juegos y Entornos Interactivos establecido por el
              Real Decreto 1583/2011, de 4 de noviembre, por el que se establece el título de
              Técnico Superior en Animaciones 3D, Juegos y Entornos Interactivos y se fijan sus
              enseñanzas mínimas.</li>
          </ul>
        </div>
      </div>
      <button data-bs-toggle="collapse" data-bs-target="#demo2" class="row"><div class="col-10">¿Para que sirve en el mundo laboral?</div> <div class="col-2 text-end"><i class="fa-solid fa-angle-down"></i></div></button>

      <div id="demo2" class="collapse">
        <div class="contdiv">
          <ul>
            <li>&nbsp; La competencia general de este curso de especialización consiste en diseñar y desarrollar
            videojuegos para diferentes dispositivos y plataformas, garantizando la experiencia del
            usuario, utilizando herramientas de última generación que permitan actuar en todas las
            fases de su desarrollo, así como aplicaciones interactivas de realidad virtual y aumentada.</li>
          </ul>
        </div>
      </div> 
      <button data-bs-toggle="collapse" data-bs-target="#demo3" class="row"><div class="col-10">¿Qué competencia general tiene el curso de especializacion?</div> <div class="col-2 text-end"><i class="fa-solid fa-angle-down"></i></div></button>

      <div id="demo3" class="collapse">
        <div class="contdiv">
          <ul>
            <li>&nbsp; La competencia general de este curso de especialización consiste en diseñar y desarrollar
              videojuegos para diferentes dispositivos y plataformas, garantizando la experiencia del
              usuario, utilizando herramientas de última generación que permitan actuar en todas las
              fases de su desarrollo, así como aplicaciones interactivas de realidad virtual y aumentada.</li>
          </ul>
        </div>
      </div> 
    </div>
  </div>
  <div class="horario">
    <table class="table table-hover">
      <thead>
        <tr>
          <th>Módulos profesionales</th>
          <th>Horas anuales</th>
          <th>Horas semanales</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>5048. Programación y motores de videojuegos. </td>
          <td>160</td>
          <td>5</td>
        </tr>
        <tr>
          <td>5049. Diseño gráfico 2D y 3D.</td>
          <td>125</td>
          <td>4</td>
        </tr>
        <tr>
          <td>5050. Programación en red e inteligencia artificial.</td>
          <td>95</td>
          <td>3</td>
        </tr>
        <tr>
          <td>5051. Realidad virtual y realidad aumentada. </td>
          <td>95</td>
          <td>3</td>
        </tr>
        <tr>
          <td>5052. Diseño, Gestión, publicación y producción.</td>
          <td>125</td>
          <td>4</td>
        </tr>
        <tr>
          <th>Total: </th>
          <th>600</th>
          <th>19</th>
        </tr>
        
      </tbody>
    </table>
  </div>
</main>

<style lang="sass">
  .portada
    background-image: url("/img/vrsmall.jpg")
    background-repeat: no-repeat
    background-size:100% 100%
    width: 100%
    height: 50vh
    display: flex
    align-items: center
    
    padding: 0rem
    font-weight: bold
    font-size: 250%
    p
      color: white
      width: 40vw
      background-color: rgba(120, 220, 220, 0.4)
      padding: 1rem
      margin-top: -2rem
  .container
    text-align: center
  .contenedorinfo
    width: 100%
    margin: 2rem 0
    

  button
    text-decoration: none
    color: white
    background-color: transparent
    border: none
    font-size: 2em
    width: 90%
    text-align: left
    box-shadow: rgb(38, 57, 77) 0px 20px 30px -10px
    background-color: #009cde
  ul
    padding: 0
    max-width: 95%
    color: white
    margin-top: 1rem
    text-align: left
    
    list-style: none
  ul li:before
    text-align: justify
    padding: .5rem 0
    font-family: FontAwesome
    content: "\f129"
    padding-left: 1rem
  .contdiv
    width: 89%
    box-shadow: rgba(255, 255, 255, 0.1) 0px 1px 1px 0px inset, rgba(50, 50, 93, 0.25) 0px 50px 100px -20px, rgba(0, 0, 0, 0.3) 0px 30px 60px -30px
    background-color: #009cde
  .horario
    margin-top: 2rem
@media screen and (max-width: 1150px)
  .portada
    font-size: 200%

@media screen and (max-width: 850px)
  .portada
    font-size: 150%
@media screen and (max-width: 770px)
  .portada
    p
      display: none
  button
    width: 100%
@media screen and (max-width: 575px)
  button
    font-size: 1.3rem
    font-weight: bolder 
  .container
    width: 100%
</style>