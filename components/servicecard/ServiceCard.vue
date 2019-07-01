<template>
    <div class="service-card">
        <div class="icon">
            <slot name="icon"></slot>
        </div>
        <h1>
            <slot name="title"></slot>
        </h1>
        <p>
            <slot></slot>
        </p>
    </div>
</template>
<style lang="stylus">
.service-card
    text-align left 
    .icon
        margin unset
        svg
            max-width 64px
    h1
        color lighten(#000,35)
        font-family 'Museo', sans-serif
        font-size 1.5rem
    p
        display block
        color lighten(black,50)
        line-height 1.5rem
</style>
