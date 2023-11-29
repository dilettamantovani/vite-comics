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
    <UpperFooter />
    <LowerFooter />
</template>

<style scoped></style>
