<template lang="pug">
.down-banner.flex.justify-around 
    .flex-col
        p Visita la tienda para que descargues nuestro APP
        .flex.gap-6
            a.down-link
                img(alt="PlayStore")
                span para android
            a.down-link
                img(alt="Apple App Store")
                span para iphone
    div
        img(src="https://loremflickr.com/200/600")

</template>
<style lang="sass">
a.down-link
    border:2px solid black
    @apply rounded py-2 px-6
.down-banner
    height: 200px
    background-color: white

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
</style>
