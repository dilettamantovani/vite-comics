<script>
import MainContent from './MainContent.vue'
import Shop from './Shop.vue'

export default {
    name: 'MainSection',
    data() {
        return {};
    },
    components: {
        MainContent,
        Shop
    }
}

</script>

<template>
    <MainContent />
    <Shop />
</template>

<style scoped></style>
