<template>
    <header class="app-head">
        <img class="app-icon" src="../../../public/img/logo.png" :alt="'HELPLINE'">
        <div class="app-info">
            <div class="app-name">COVID-19 Helper Chatbot</div>
            <div class="app-poweredby">Built for <a target="_blank" rel="noopener noreferrer" href="https://www.hackcovit.com/" aria-hidden="true">hackcovit</a></div>
        </div>
        <slot />
    </header>
</template>

<style lang="sass" scoped>
@import '@/Style/Mixins'

.app-head
    z-index: 666
    padding: 10px
    padding-top: 15px
    position: fixed
    width: 100%

    @media screen and (max-width: 1000px)
        background-color: var(--background)

    .app-icon
        border-radius: 8px
        width: 50px
        height: 50px
        object-fit: contain
        background-color: transparent

    .app-info
        display: inline-block
        margin-left: 10px

        .app-name
            font-size: 18px
            font-weight: 500
            color: var(--text)
            line-height: 15px
            padding-bottom: 2px

        .app-poweredby
            color: var(--text-secondary)
            font-size: 14px

            a[href]
                color: var(--text-secondary)
                text-decoration: none
                transition: color 300ms 
                &:hover
                    color: var(--text-tertiary)

.audio-toggle
    @include reset
    display: flex
    position: fixed
    top: 0
    right: 0
    margin: 8.5px 0
    z-index: 999
    padding: 8px
    margin-top: 15px
    background-color: var(--element-background)
    border-radius: 20px 0 0 20px
    cursor: pointer
    color: var(--text)
    transition: padding .25s ease

    &:focus
        outline: 0 !important
        
    &:hover
        padding-right: 20px
</style>

<script>
export default {
    name: 'TopHead',
    props: {
        app: {
            type: Object,
            default: null
        }
    }
}
</script>