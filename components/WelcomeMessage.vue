<template lang="pug">
div.banner
    div.p-12.flex.flex-col.items-center
        p.mb-16
            strong ¿Va a visitar a Cuba pronto? 
            span.font-thin Conozca qué debe tener en cuenta para su visita
        .justify-center.flex
        a.border-2.border-black.rounded.p-2.px-8 &rsaquo; 
</template>
<style lang="sass">
.banner
    height: 200px
    background-color: orange
    // background: url("https://dummyimage.com/10x10/f80/ff5")
    background: url("https://loremflickr.com/800/200")

    /* ¿Va a visitar a Cuba */
    position: relative
    width: 100%
    height: 411px

    font-family: 'Manrope',sans-serif
    font-style: normal
    font-size: 48px
    line-height: 60px
    /* or 125% */
    color: #2C2F33
    margin-bottom: 300px

    div
        /* Rectangle */
        box-sizing: border-box

        position: absolute
        // width: 597px
        // height: 506px
        max-width:500px
        left: 25px
        top: 91px

        background: rgba(253, 189, 49, 0.85)
        border: 1px solid rgba(155, 218, 214, 0.0001)
        border-radius: 8px
</style>
