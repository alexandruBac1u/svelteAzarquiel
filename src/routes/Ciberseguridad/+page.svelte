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
            <li>&nbsp; Título de Técnico Superior en Administración de Sistemas Informáticos en Red establecido por el Real Decreto 1629/2009, de 30 de octubre.</li>
            <li>&nbsp; Título de Técnico Superior en Desarrollo de Aplicaciones Multiplataforma, establecido por el Real Decreto 450/2010, de 16 de abril.</li>
            <li>&nbsp; Título de Técnico Superior en Desarrollo de Aplicaciones Web, establecido por el Real Decreto 686/2010, de 20 de mayo.</li>
            <li>&nbsp; Título de Técnico Superior en Sistemas de Telecomunicaciones e Informáticos, establecido por el Real Decreto 883/2011, de 24 de junio.</li>
            <li>&nbsp; Título de Técnico Superior en Mantenimiento Electrónico establecido por el Real Decreto 1578/2011, de 4 de noviembre</li>
          </ul>
        </div>
      </div>
      <button data-bs-toggle="collapse" data-bs-target="#demo2" class="row"><div class="col-10">¿Para que sirve en el mundo laboral? (Salidas)</div> <div class="col-2 text-end"><i class="fa-solid fa-angle-down"></i></div></button>

      <div id="demo2" class="collapse">
        <div class="contdiv">
          <ul>
            <li>&nbsp; Experto/a en ciberseguridad.</li>
            <li>&nbsp; Auditor/a de ciberseguridad.</li>
            <li>&nbsp; Consultor/a de ciberseguridad.</li>
            <li>&nbsp; Hacker ético.</li>
          </ul>
        </div>
      </div> 
      <button data-bs-toggle="collapse" data-bs-target="#demo3" class="row"><div class="col-10">¿Cuáles son las salidas profesionales?</div> <div class="col-2 text-end"><i class="fa-solid fa-angle-down"></i></div></button>

      <div id="demo3" class="collapse">
        <div class="contdiv">
          <ul>
            <li>&nbsp; Este profesional ejercerá su actividad en entidades de los sectores donde sea necesario establecer mecanismos y medidas para la protección de los sistemas de información y redes de comunicaciones.</li>
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
          <td>5021. Incidentes de ciberseguridad </td>
          <td>120</td>
          <td>5</td>
        </tr>
        <tr>
          <td>5023. Puesta en producción segura</td>
          <td>185</td>
          <td>7</td>
        </tr>
        <tr>
          <td>5024. Análisis forense informático</td>
          <td>120</td>
          <td>5</td>
        </tr>
        <tr>
          <td>5025. Hacking ético </td>
          <td>120</td>
          <td>5</td>
        </tr>
        <tr>
          <td>5026. Normativa de ciberseguridad</td>
          <td>55</td>
          <td>2</td>
        </tr>
        <tr>
          <th>Total: </th>
          <th>720</th>
          <th>54</th>
        </tr>
        
      </tbody>
    </table>
  </div>
</main>

<style lang="sass">
  .portada
    background-image: url("/img/hacker.jpg")
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
    max-width: 90%
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

@media screen and (max-width: 575px)
  button
    font-size: 1.3rem
    font-weight: bolder 
</style>