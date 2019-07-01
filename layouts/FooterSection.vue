<template>
    <div class="footer-wrapper">
        <footer>
        <div class="item">
            <h3>SpaceDrive</h3>
            <p>4615 N. University Drive, Coral Springs,FL 2315 (800) 532-3124</p>
        </div>
        <div class="item">
            <h3>Quick Links</h3>
            <a href="#">Domain</a>
            <a href="#">Hosting</a>
            <a href="#">WHMCS</a>
            <a href="#">Blog</a>
            <a href="#">Contact</a>
        </div>
        <div class="item">
            <h3>Support</h3>
            <a href="#">Product Support</a>
            <a href="#">Community</a>
            <a href="#">Report Abuse</a>
        </div>
        <div class="item">
            <h3>Account</h3>
            <a href="#">My Account</a>
            <a href="#">My Renewals</a>
            <a href="#">Create Account</a>
            <a href="#">My Plan</a>
        </div>
        <div class="item">
            <h3>News letter</h3>
            <div class="subscription-input">
                <input type="text" placeholder="Email address"/>
                <button>Join</button>
            </div>
        </div>
    </footer>
    <copyright-section />
    </div>
</template>
<script>
import CopyrightSection from './CopyrightSection'
export default {
    components:{
        CopyrightSection
    }
}
</script>

<style lang="stylus">
.footer-wrapper
    padding 4rem
    background darken(#2708a2,20)
footer
    display flex
    overflow-y auto
    color white
    .item
        margin 0 48px
        max-width 200px
        a
            color darken(white,20)
            text-decoration unset
            display block
            margin 20px 0
    .subscription-input
        position relative
        box-sizing border-box
        display inline-block
        input
            border unset
            margin unset
            box-sizing border-box
            outline unset
            background white
            border-radius 100px
            padding 0.6rem 1rem
        button 
            position absolute
            color white
            font-weight bold
            z-index 10
            cursor pointer
            border unset
            outline unset
            background #d55e54
            border-top-right-radius 100px
            border-bottom-right-radius 100px
            right 0
            margin unset
            top 0
            height 100%
            padding 0 1rem
</style>
