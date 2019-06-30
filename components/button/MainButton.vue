<template>
    <button class="main-button">
        <slot>Button</slot>
    </button>
</template>
<style lang="stylus">
.main-button 
    background #d55e54
    border unset
    padding 0.8rem 2rem
    color white
    border-radius 1000px
    font-size 0.7rem
    outline unset
    font-weight bold
    text-transform uppercase
    cursor pointer
    box-shadow: 0px 1px 5px -1px rgba(0,0,0,0.2), 0px 1px 10px 0px rgba(0,0,0,0.14), 0px 1px 18px 0px rgba(0,0,0,0.12)
</style>
