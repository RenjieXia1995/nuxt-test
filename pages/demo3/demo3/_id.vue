<template>
    <div>
        这是demo3的子路由，接收的参数是{{ params }}
    </div>
</template>

<script>
export default {
    data() {
        return {
            params:this.$route.params.id
        }
    },
}
</script>