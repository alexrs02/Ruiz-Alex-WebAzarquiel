<main>
    <div class="container-contact d-flex flex-row justify-content-around">
        <div class="icons d-flex align-items-center justify-content-center">
            <a href="https://www.facebook.com/people/iesazarquiel/100088978323687/">
                <i class="fa fa-facebook" />
            </a>
            <a href="http://twitter.com/iesazarquiel">
                <i class="fa fa-twitter" />
            </a>
            <a href="https://vimeo.com/user40137199">
                <i class="fa fa-youtube" />
            </a>
            <a href="https://www.flickr.com/photos/iesazarquiel/albums">
                <i class="fa fa-flickr" />
            </a>
            <a href="https://www.flickr.com/photos/iesazarquiel/albums">
                <i class="fa fa-flickr" />
            </a>
            <a href="https://www.instagram.com/iesazarquiel/">
                <i class="fa fa-instagram" />
            </a>
        </div>
        <div class="urls flex-row d-flex align-items-center justify-content-center">
            <div class="telf">
                <i class="fa fa-phone" />
                <a href="tel:925284043">925284043</a>
            </div>
            <div class="email">
                <i class="fa fa-envelope" />
                <a href="mailto:45003875.ies@edu.jccm.es">
                   45003875.ies@edu.jccm.es
                </a>
            </div>
        </div>
    </div>
</main>

<style lang="sass">
    @use '../style/_colors.sass'
    main
        background-color: #F5F5F5
        // overflow-x: hidden

    .container-contact
        width: 100%
        height: 4vh

    i
        color: gray
        font-size: .8rem
        padding: 0 0.4rem
        transition: 300ms
        &:hover
            color: colors.$hover-color-blue
    .icons  
        height: 100%
        a
            margin: 0
            padding: 0
    .urls
        column-gap: 1rem
        a
            font-size: .8rem
            color: colors.$hover-color-blue
            text-decoration: none
            transition: 300ms
            &:hover
                color: colors.$hover-color-blue

    @media (max-width: 768px)
        .container-contact
            flex-direction: column !important
            row-gap: 1rem
            height: 6vh
            padding: 2.8rem 0
</style>
