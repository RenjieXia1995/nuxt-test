<template>
    <div>这是demo2 它携带的参数是{{params}}</div>
</template>

<script>
export default {
    data() {
        return {
            params:this.$route.params.params

        }
    },
}
</script>