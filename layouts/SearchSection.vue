<template>
    <div class="search-section">
        <h1 class="search-title">Search Your Domain</h1>
        <div class="search-box">
            <input placeholder="Search Your Domain"/>
            <div class="right-side">
                <p>.com</p>
                <button>Search</button>
            </div>
        </div>
        <div class="tld-pricing">
            <span>.COM $9.99</span>
            <span>.NET $7.54</span>
            <span>.ORG $7.54</span>
            <span>.CO $7.54</span>
            <span>.UK $7.54</span>
        </div>
    </div>
</template>
<style lang="stylus">
.search-section
    position relative
    z-index 10
    margin-top 40vh
    font-family 'Museo'
    .search-title
        color white
        text-align center
    .search-box
        display flex
        position relative
        align-items center
        margin 2rem auto
        width 36vw
        height 48px
        input
            position absolute
            left 0
            padding 0.7rem
            padding-left 2rem
            width 100%
            box-sizing border-box
            border-radius 1000px
            border unset
            outline unset
            height 100%
        .right-side
            height 100%
            display flex            
            position absolute
            right -10px
            p
                margin auto 20px
            button 
                border-radius 1000px
                border unset
                background-image: linear-gradient(to right, #f170ce , #592db3)
                color white
                padding 0 2rem
                font-weight bold
                font-size 1rem
                cursor pointer
                outline none
                height 100%
.tld-pricing
    color white
    text-align center
    font-family 'Poppins', sans-serif
    span
        margin 0 10px
        font-size 0.8rem
        
@media (max-width: 1000px)
    .search-box
        width 90% !important
</style>

