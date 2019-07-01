<template>
    <div class="highlight-section">
        <div class="section">
            <first-highlight-decoration />
            <h1>Secure website services</h1>
            <p>Domain registeration is The Process of Registering A Domain Name, Which Identifies One Or More IP Addresses With A Name That Is Easier To Remember And Use In Urls To Identify Particular Web Pages. The Person Or Business That Registers Domain Name Is Called The Domain Name Registrant.</p>
            <div class="check-box-item">
                <checkbox-icon />
                <p>Web Asset Delivery</p>
            </div>
            <div class="check-box-item">
                <checkbox-icon />
                <p>24/7 Dedicated Support</p>
            </div>
            <div class="check-box-item">
                <checkbox-icon />
                <p>Global Datacenters</p>
            </div>
            <p><a href="#">Read More...</a></p>
        </div>
        <div class="section second">
            <second-highlight-decoration />
            <div class="text">
                <h1>Secure domain registeration</h1>
                <p>Domain registeration is The Process of Registering A Domain Name, Which Identifies One Or More IP Addresses With A Name That Is Easier To Remember And Use In Urls To Identify Particular Web Pages. The Person Or Business That Registers Domain Name Is Called The Domain Name Registrant.</p>
                <div class="check-box-item">
                    <checkbox-icon />
                    <p>Web Asset Delivery</p>
                </div>
                <div class="check-box-item">
                    <checkbox-icon />
                    <p>24/7 Dedicated Support</p>
                </div>
                <div class="check-box-item">
                    <checkbox-icon />
                    <p>Global Datacenters</p>
                </div>
                <p><a href="#">Read More...</a></p>
            </div>
        </div>
    </div>
</template>
<script>
import MainButton from '../components/button/MainButton'
import FirstHighlightDecoration from '../components/art/FirstHighlightDecoration'
import SecondHighlightDecoration from '../components/art/SecondHighlightDecoration'
import CheckboxIcon from '../components/art/icons/CheckboxIcon'
export default {
    components:{
        MainButton,
        FirstHighlightDecoration,
        CheckboxIcon,
        SecondHighlightDecoration
    }
}
</script>

<style lang="stylus">
.highlight-section
    width 100%
    box-sizing border-box
    padding 8rem 8rem
    color white
    position relative
    .check-box-item
        display flex
        align-items center
        margin-top 20px
        svg
            width 32px
        p
            margin 10px
    .section
        position relative
        max-width 100%
        &.second
            .text
                max-width 50%
                display block
                margin-left  auto
            margin-top 30vh
            margin-left auto
    a
        font-weight bold
    h1
        font-family: 'Museo', sans-serif
        position relative
        z-index 1
    p
        position relative
        z-index 1
        color darken(white,10)
        font-family: 'Poppins', sans-serif
        margin-top 2rem
        max-width 40vw
        line-height 1.7rem
</style>
