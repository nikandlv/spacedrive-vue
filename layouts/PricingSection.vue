<template>
    <div class="pricing-section">
        <h1>Choose your plan</h1>
        <p>We have many plans that may suite your needs for any web hosting and private servers</p>
        <div class="cards">
            <grid>
            <row center="xs">
                <column :xs="12" :md="3">
                    <pricing-card>
                        <template v-slot:title>Professional</template>
                        <template v-slot:space>500</template>
                        <template v-slot:spaceunit>GB</template>
                        <template v-slot:domains>2</template>
                        <template v-slot:ssd>300</template>
                        <template v-slot:price>$ 49.9/ Month</template>
                    </pricing-card>
                </column>
                <column :xs="12" :md="3">
                    <pricing-card>
                        <template v-slot:title>Advanced</template>
                        <template v-slot:space>300</template>
                        <template v-slot:spaceunit>GB</template>
                        <template v-slot:domains>1</template>
                        <template v-slot:ssd>100</template>
                        <template v-slot:price>$ 29.9/ Month</template>
                    </pricing-card>
                </column>
                <column :xs="12" :md="3">
                    <pricing-card>
                        <template v-slot:title>Starter</template>
                        <template v-slot:space>150</template>
                        <template v-slot:spaceunit>GB</template>
                        <template v-slot:domains>No</template>
                        <template v-slot:ssd>32</template>
                        <template v-slot:price>$ 12.9/ Month</template>
                    </pricing-card>
                </column>
            </row>
        </grid>
        </div>
    </div>
</template>
<script>
import PricingCard from '../components/pricingcard/PricingCard'
export default {
    
    components:{
        PricingCard
    }
}
</script>

<style lang="stylus">
.pricing-section
    background url(../static/img/datacenter-full.jpg) no-repeat center center fixed
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
        text-align center
    p
        display block
        margin 0 auto
        position relative
        text-align center
        z-index 1
        color darken(white,20)
        font-family: 'Poppins', sans-serif
        margin-top 2rem
        max-width 40vw
    .cards
        margin-top 50px
.pricing-section:before
        content ''
        width 100%
        height 100%
        position absolute 
        left 0
        top 0
        background rgba(#2708a2,0.6)
@media (max-width 900px)
    .pricing-section
        padding 8rem 1rem
</style>
