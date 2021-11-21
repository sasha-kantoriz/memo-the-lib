<template>
    <v-for book in {{books}}>
        <book/>
    <endfor/>
</template>

<script>
import book from "@/components/book.vue";

export default {
    name: 'library',
    components: {
        book
    }
}
</script>

<style lang="scss" scoped>

</style>>
