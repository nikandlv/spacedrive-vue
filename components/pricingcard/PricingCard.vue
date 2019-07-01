<template>
    <div class="pricing-card">
        <h1><slot name="title">Basic</slot></h1>
        <span class="space"><slot name="space">500</slot><span class="sub"><slot name="spaceunit">GB</slot></span></span>
        <p><slot name="domains"></slot> Free Domain</p>
        <p><slot name="ssd"></slot> GB SSD Disk</p>
        <p><slot name="extra1">Special Offers</slot></p>
        <p><slot name="extra2">Unlimited Support</slot></p>
        <p class="price"><slot name="price">$ 0.80/ Month</slot></p>
        <span class="buy-now">
            Buy Now
        </span>
    </div> 
</template>
<style lang="stylus">
.pricing-card
    position relative
    z-index 10
    padding 3rem
    background white
    margin 10px
    border-radius 16px
    background-image: linear-gradient( #f170ce, #d55e54)
    .buy-now
        position absolute
        bottom 7%
        right 0px
        font-size 1rem
        font-weight bold
        transform rotate(-45deg)
        color white
    &:before
        content ''
        background white
        width 100%
        height 100%
        position absolute
        top 0
        left 0
        border-radius 16px
        border-bottom-right-radius 60%
    h1
        font-size 1rem
        text-transform uppercase
        color #2708a2
        padding-bottom 30px
    p
        color lighten(black,40)
        font-size 0.9rem
    .price
        color black
    .space
        position relative
        font-size 2rem
        color black
        span 
            position absolute 
            right -30px
            top -10px
            font-size 0.9rem
</style>
