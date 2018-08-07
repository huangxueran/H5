<!--<template> 11-->
    <!--<div>-->
        <!--<h2>商品列表页</h2>-->
    <!--</div>-->
<!--</template>-->

<!--<script>-->
    <!--export default {-->

    <!--}-->
<!--</script>-->

<!--<style>-->

<!--</style>-->

<template>
    <div>
        <h2>商品列表页</h2>
    </div>
</template>

<script>
    export default {
        created(){
            console.log(this.$route.query.id)
        }
    }
</script>

<style>

</style>