<template>
    <div class="feature-card">
        <div class="icon">
            <slot name="icon"></slot>
        </div>
        <span class="title"><slot name="title"></slot></span>
        <p>
            <slot></slot>
        </p>
    </div>
</template>
<style lang="stylus">
.feature-card
    background white
    border-radius 12px
    padding 1rem
    margin-top 100px
    position relative
    z-index 10
    .icon
        display block
        margin 0 auto
        svg
            width 64px
    .title
        text-align center
        font-size 1rem
    p
        color lighten(black,30)
        font-size 0.9rem
</style>
