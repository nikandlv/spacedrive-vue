<template>
    <grid>
        <row center="xs">
            <column :xs="12" :md="3">
                <feature-card>
                    <template v-slot:icon>
                        <backup-icon />
                    </template>
                    <template v-slot:title>
                        Cloud Backup
                    </template>
                    The same day that we receive your items, one of our numismatist will be contacting you with outNo bligation to sell offer.
                </feature-card>
            </column>
            <column :xs="12" :md="3">
                <feature-card>
                    <template v-slot:icon>
                        <security-icon />
                    </template>
                    <template v-slot:title>
                        Data Security
                    </template>
                    The same day that we receive your items, one of our numismatist will be contacting you with outNo bligation to sell offer.
                </feature-card>
            </column>
            <column :xs="12" :md="3">
                <feature-card>
                    <template v-slot:icon>
                        <update-icon />
                    </template>
                    <template v-slot:title>
                        Free Update
                    </template>
                    The same day that we receive your items, one of our numismatist will be contacting you with outNo bligation to sell offer.
                </feature-card>
            </column>
        </row>
    </grid>
</template>
<script>
import FeatureCard from '../components/featurecard/FeatureCard'
import UpdateIcon from '../components/art/icons/UpdateIcon'
import SecurityIcon from '../components/art/icons/SecurityIcon'
import BackupIcon from '../components/art/icons/BackupIcon'
export default {
    components:{
        FeatureCard,
        UpdateIcon,
        SecurityIcon,
        BackupIcon
    }
}
</script>
