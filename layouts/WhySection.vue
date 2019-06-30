<template>
    <div class="why-section">
        <h1>Why choose us</h1>
        <p>Domain registeration is The Process of Registering A Domain Name, Which Identifies One Or More IP Addresses With A Name That Is Easier To Remember And Use In Urls To Identify Particular Web Pages. The Person Or Business That Registers Domain Name Is Called The Domain Name Registrant.</p>
        <p>Domain registeration is The Process of Registering A Domain Name, Which Identifies One Or More IP Addresses With A Name That Is Easier To Remember And Use In Urls To Identify Particular Web...</p>
        <main-button>
            read more
        </main-button>
        <why-section-decoration />
    </div>
</template>
<script>
import MainButton from '../components/button/MainButton'
import WhySectionDecoration from '../components/art/WhySectionDecoration'
export default {
    components:{
        MainButton,
        WhySectionDecoration
    }
}
</script>

<style lang="stylus">
.why-section
    background url(../static/img/datacenter-mini.jpg) no-repeat center center fixed
    -webkit-background-size cover
    -moz-background-size cover
    -o-background-size cover
    background-size cover
    margin-top 150px
    width 100%
    box-sizing border-box
    padding 8rem 8rem
    color white
    position relative
    button 
        position relative
        margin-top 30px
        z-index 1
    h1
        font-family: 'Museo', sans-serif
        position relative
        z-index 1
    p
        position relative
        z-index 1
        color darken(white,20)
        font-family: 'Poppins', sans-serif
        margin-top 2rem
        max-width 40vw
.why-section:before
        content ''
        width 100%
        height 100%
        position absolute 
        left 0
        top 0
        background rgba(#2708a2,0.6)
</style>
