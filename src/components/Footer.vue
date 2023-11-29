<script>
import UpperFooter from "./UpperFooter.vue"
import LowerFooter from "./LowerFooter.vue"

export default {
    name: 'Footer',
    data() {
        return {};
    },
    components: {
        UpperFooter,
        LowerFooter
    }
}

</script>

<template>
    <footer class="row">
        <UpperFooter />
        <LowerFooter />
    </footer>
</template>

<style scoped>
.row {
    margin: 0 auto;
}
</style>
