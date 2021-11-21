<template>
    <library books={{books}}/>
</template>

<script>
import library from "@/components/library.vue"

export default {
    name: 'Art',
    components: {
        library
    },
    data: {
        books: {} /*read JSON file mock*/
    }
}
</script>

<style lang="scss" scoped>

</style>>
