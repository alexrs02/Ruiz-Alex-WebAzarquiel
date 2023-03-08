<main>
    <div class="container-nav" id="contenido">
        <div
            class="container d-flex flex-row align-items-center justify-content-around"
        >
            <div class="img-container ">
                <a href="../"><img src="img/logoies.png" alt="LogoIes" /></a>
            </div>
            <div
                class="links d-flex flex-row align-items-center .justify-content-center"
            >
                <div class="nav-container">
                    <a href="../">INICIO</a>
                    <a href="f">AL DIA <i class="fa-solid fa-angle-down" /></a>
                    <a href="f">EL LORO</a>
                    <a href="f"
                        >EL CENTRO <i class="fa-solid fa-angle-down" /></a
                    >
                    <a href="f"
                        >SECRETARIA <i class="fa-solid fa-angle-down" /></a
                    >
                    <a href="f">FAMILIAS <i class="fa-solid fa-angle-down" /></a
                    >
                    <a href="f">BOLSA</a>
                </div>
                <div class="bars-container">
                    <a
                        class="bara"
                        data-bs-toggle="offcanvas"
                        href="#offcanvasExample"
                        role="button"
                        aria-controls="offcanvasExample"
                        ><i class="fa-solid fa-bars" /></a
                    >
                </div>
            </div>
        </div>
    </div>
    <div
        class="offcanvas offcanvas-end"
        tabindex="-1"
        id="offcanvasExample"
        aria-labelledby="offcanvasExampleLabel"
    >
        <div class="offcanvas-header">
            <h5 class="offcanvas-title" id="offcanvasExampleLabel">Search</h5>
            <button
                type="button"
                class="btn-close btn-close-white"
                data-bs-dismiss="offcanvas"
                aria-label="Close"
            />
        </div>

        <div class="offcanvas-body">
            <input
                class="form-control me-2"
                type="search"
                placeholder="Search"
                aria-label="Search"
            />
            <hr />
            <div class="group-list d-flex flex-column justify-content-center align-items-center">
                <a href="../"><i class="fa-solid fa-angle-right"> </i>INICIO</a>
                <a href="f"><i class="fa-solid fa-angle-right"></i> AL DIA</a>
                <a href="f"><i class="fa-solid fa-angle-right"></i> EL LORO</a>
                <a href="f"><i class="fa-solid fa-angle-right"></i> EL CENTRO</a>
                <a href="f"><i class="fa-solid fa-angle-right"></i> SECRETARÍA</a>
                <a href="f"><i class="fa-solid fa-angle-right"></i> FAMILIAS</a>
                <a href="f"><i class="fa-solid fa-angle-right"></i> BOLSA</a>
            </div>
        </div>
    </div>
</main>

<style lang="sass">
    @use '../style/_colors.sass'
    .offcanvas-body
        padding: 0
        width: 100%
    .group-list
        width: 100%
        i
            color: white
            font-size: 0.7rem
            padding-right: 0.2rem
        a
            padding: 1rem
            display: flex
            align-items: center
            width: 100%
            border-bottom: 1px solid rgb(80,80,80)
            color: white
            text-decoration: none
            height: 3rem
            &:hover
                background-color: rgb(80,80,80)
      

    .form-control
        margin:1rem
        width: 22rem
    .offcanvas
        background-color: #3D3D3D
        color: white

    .bara
        color: black
        text-decoration: none
        
    .container-nav
        padding: 1rem 0 1rem 0
        

    .nav-container
        text-align: right
        padding: 0 1rem 0 8rem
        
        a
            text-decoration: none
            color: black
            padding: 0.8rem
            font-size: 0.8rem
            transition: 300ms
            
            &:hover
                color: colors.$hover-color-blue
            i
                
                font-size: 0.6rem

    .bars-container
        
        i
            font-weight: bold
            font-size: 1.2rem
            transition: 300ms
            padding-top: .4rem
            &:hover
                color: colors.$hover-color-blue
                cursor: pointer
        text-align: left
    img
        max-width: 100%
        width: 17rem

    @media (max-width: 1200px)
        .nav-container
            display: none
            
        .container
            padding: 0 2rem 0 2rem !important
            justify-content: space-between !important
            max-width: 100% !important
            
        
    @media (max-width: 700px)
        img
            width: 15rem
</style>
