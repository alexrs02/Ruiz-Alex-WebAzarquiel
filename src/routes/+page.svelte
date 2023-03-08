<main>
  <div class="container">
    <div class="caja d-flex row align-items-center justify-content-center">
      <div
        class="card card-uno  col-lg-6 col-md-6 col-sm-12"
        style="width: 18rem"
      >
        <img
          src="img/videogames.jpg"
          class="card-img-top"
          alt="videogamesphoto"
        />
        <div class="card-body">
          <h5 class="card-title">Curso de Especialización</h5>
          <p class="card-text">
            Desarrollo de <b>Videojuegos</b> y Realizad Virtual.
          </p>
          <a href="games/" class="btn btn-primary">Saber mas...</a>
        </div>
      </div>
      <div
        class="card card-dos col-lg-6 col-md-6 col-sm-12"
        style="width: 18rem"
      >
        <img
          src="img/cibersecurity.jpg"
          class="card-img-top"
          alt="cibersecurityphoto"
        />
        <div class="card-body">
          <h5 class="card-title">Curso de Especialización</h5>
          <p class="card-text">
            <b>Ciberseguridad</b> en Entornos de las Tecnologías de la Información.
          </p>
          <a href="/ciber" class="btn btn-primary">Saber mas...</a>
        </div>
      </div>
    </div>
  </div>
</main>

<style lang="sass">
  .caja 
    column-gap: 2rem
    height: 51.6vh
  

  .card 
    margin-top: 2rem
    margin-bottom: 2rem
    transition: all 0.2s ease-in-out
  
  .card:hover 
    transform: scale(1.1) 
  
  .row 
    --bs-gutter-x: 0
  
  @media (max-width: 768px) 
    .caja 
      height: 100%
    
  

  .caja 
    animation-duration: 3s
    animation-name: slidein
  

  @keyframes slidein 
    from 
      margin-left: 50%
    

    to 
      margin-left: 0%
    

</style>
