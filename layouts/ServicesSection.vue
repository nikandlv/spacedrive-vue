<template>
    <div class="services-section">
        <div class="title-section">
            <h1>Our Services</h1>
            <p>Domain registeration is The Process of Registering A Domain Name, Which Identifies One Or More IP Addresses With A Name That Is Easier</p>
        </div>
        <div class="card-section">
            <grid>
            <row center="xs">
                <column :xs="12" :md="4">
                    <service-card>
                        <template v-slot:icon>
                            <shared-hosting />
                        </template>
                        <template v-slot:title>
                            Shared Hosting
                        </template>
                        Shared Hosting is Web hosting in which the service provider serves pages for multiple web sites, each having its own Internet domain name, from a single Web server, although shared hosting is a less...
                    </service-card>
                </column>
                <column :xs="12" :md="4">
                    <service-card>
                        <template v-slot:icon>
                            <dedicated-hosting />
                        </template>
                        <template v-slot:title>
                            Dedicated Hosting
                        </template>
                        Dedicated Hosts. An Amazon EC2 Dedicated Host is a physical server with EC2 instance capacity fully dedicated to your use. Dedicated Hosts allow you to use your existing per-socket, per-core...
                    </service-card>
                </column>
                <column :xs="12" :md="4">
                    <service-card>
                        <template v-slot:icon>
                            <cloud-hosting />
                        </template>
                        <template v-slot:title>
                            Cloud Hosting
                        </template>
                        Cloud hosting is the procurement of computing resources from a cloud computing provider or facility to host data, services and/or solutions. Cloud hosting is an Infastructer as a service...
                    </service-card>
                </column>
                                <column :xs="12" :md="4">
                    <service-card>
                        <template v-slot:icon>
                            <domain-registeration />
                        </template>
                        <template v-slot:title>
                            Domain Registeration
                        </template>
                        Domain registeration is The Process of Registering A Domain Name, Which Identifies One Or More IP Addresses With A Name That Is Easier To Remember And Use In Urls To Identify Particular Web Pages...
                    </service-card>
                </column>
                <column :xs="12" :md="4">
                    <service-card>
                        <template v-slot:icon>
                            <v-p-s-hosting />
                        </template>
                        <template v-slot:title>
                            VPS Hosting
                        </template>
                        How much VPS Hosting costs? As a result of VPS hosting hybrid nature, it costs isn't quite as low as shared hosts fees, but its not nearly as high as dedicated hosts fees, You can expect to pay between...
                    </service-card>
                </column>
                <column :xs="12" :md="4">
                    <service-card>
                        <template v-slot:icon>
                            <reseller-hosting />
                        </template>
                        <template v-slot:title>
                            Reseller Hosting
                        </template>
                        Reseller hostin is a form of web hosting wherein the account owner has the ability to use his or her allotted hard drive space and bandwidth to host websites on behalf of third parties. The resller purchases...
                    </service-card>
                </column>
            </row>
        </grid>
        </div>
    </div>
</template>
<style lang="stylus">
.services-section
    padding 8rem 4rem
    background white
    .card-section
        margin-top 75px
    .title-section
        h1
            color lighten(#2708a2,35)
            text-align center
            font-family 'Museo', sans-serif
            font-size 1.5rem
        p
            text-align center
            max-width 50%
            display block
            margin 0 auto
            color lighten(black,40)
</style>

<script>
import ServiceCard from '../components/servicecard/ServiceCard'
import CloudHosting from '../components/art/icons/CloudHosting'
import DedicatedHosting from '../components/art/icons/DedicatedHosting'
import DomainRegisteration from '../components/art/icons/DomainRegisteration'
import ResellerHosting from '../components/art/icons/ResellerHosting'
import VPSHosting from '../components/art/icons/VPSHosting'
import SharedHosting from '../components/art/icons/SharedHosting'
export default {
    components:{
        ServiceCard,
        CloudHosting,
        DedicatedHosting,
        DomainRegisteration,
        ResellerHosting,
        SharedHosting,
        VPSHosting
    }
}
</script>
