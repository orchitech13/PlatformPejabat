<template>
    <div class="tentangkami">
        <v-responsive :aspect-ratio="16/9">
            <Header />
            <IsiTentangKami />
        </v-responsive>
    </div>
</template>

<script>
import Header from '@/components/Header.vue'
import IsiTentangKami from '@/components/IsiTentangKami.vue'
export default {
    name: 'TentangKami',
    components: {
        Header,
        IsiTentangKami,
    }
}
</script>