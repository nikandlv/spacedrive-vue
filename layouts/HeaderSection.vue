<template>
    <header>
        <TopbarDecoration />
        <div class="top-bar">
            <p>support@nikandlv.ir</p>
            <div class="divider" />
            <p class="push-end">+989300123123</p>
            <p><a href="#">Live chat</a></p>
            <p><a href="#">Login</a></p>
            <p><a href="#">Support</a></p>
        </div>
        <nav>
            <a class="logo" href="#">Space<span>Drive</span></a>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Domain</a></li>
                <li><a href="#">Hosting</a></li>
                <li><a href="#">WHMCS</a></li>
                <li><a href="#">Blog</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
        <div>
            <div class="about-section">
                <h1>Powerful</h1>
                <h1>Hosting Service</h1>
                <h1>Provider</h1>
                <p>Millions of customers rely on our products to get their ideas online</p>
                <main-button>Buy now</main-button>
            </div>
            <header-decoration />
        </div>
    </header>
</template>
<script>
import TopbarDecoration from '../components/art/TopbarDecoration'
import MainButton from '../components/button/MainButton'
import HeaderDecoration from '../components/art/HeaderDecoration'
export default {
    components:{
        TopbarDecoration,
        HeaderDecoration,
        MainButton
    }
}
</script>

<style lang="stylus">
nav 
    display flex
    padding 2rem 4rem
    position relative
    overflow-x auto
    z-index 10
    .logo
        flex-grow 1
        font-size 1.4rem
        font-family 'Museo', sans-serif
        span
            font-weight bold
    ul
        display flex
        margin 0
        li
            display inline
            margin 0 20px
            font-weight bold
            font-size 0.9rem
header 
    position relative
    .about-section
        margin-top 50px
        padding 0rem 8rem
        position relative
        z-index 10
        color white
        h1
            font-family 'Museo', sans-serif
            font-weight 100
            font-size 3rem
            line-height 3rem
            margin 0
        p
            font-weight 1rem
            max-width 23vw
            color darken(white,10)
    .top-bar
        display flex
        padding 0.5vh 14vw
        align-items  center
        background rgba(white,0.05)
        position relative
        overflow-x auto
        z-index 1
        .divider
            height 3vh
            width 1px
            background rgba(white,0.3)
        p
            color white
            margin 1vw
            white-space pre
            font-size 0.9rem
        .push-end
            flex-grow 1
@media (max-width 900px)
    .about-section
        padding 0rem 1rem !important
        h1
            background-color white
            color black
            display table
        p
            background-color white
            color black !important
            padding 1rem
</style>
