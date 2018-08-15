<!--<template>  1-->
    <!--<div>-->
        <!--<h2>新闻页面</h2>-->
    <!--</div>-->
<!--</template>-->

<!--<script>-->
    <!--export default {-->
        <!--name: "News"-->
    <!--}-->
<!--</script>-->

<!--<style scoped>-->

<!--</style>-->

<!--<template> 2-->
    <!--<div>-->
        <!--<h2>新闻页面</h2>-->
        <!--<button @click="prev">返回上一级</button>-->
    <!--</div>-->
<!--</template>-->

<!--<script>-->
    <!--export default {-->
        <!--methods: {-->
            <!--prev() {-->
                <!--this.$router.go(-1)-->
                <!--//route 表示可读的  router表示获取Vue实例上的一些功能函数-->
            <!--}-->
        <!--}-->
    <!--}-->
<!--</script>-->

<!--<style scoped>-->

<!--</style>-->

<!--<template> 3-->
    <!--<div>-->
        <!--<h2>新闻页面</h2>-->
        <!--<button @click="prev">返回上一级</button>-->
    <!--</div>-->
<!--</template>-->

<!--<script>-->
    <!--export default {-->
        <!--methods: {-->
            <!--prev() {-->
                <!--this.$router.go(-1)-->
                <!--//route 表示可读的  router表示获取Vue实例上的一些功能函数-->
            <!--}-->
        <!--}-->
    <!--}-->
<!--</script>-->

<!--<style scoped>-->

<!--</style>-->

<template>
    <div>
        <h2>新闻页面</h2>
        <button @click="prev">返回上一级</button>
    </div>
</template>

<script>
    export default {
        methods: {
            prev() {
                this.$router.go(-1)
                //route 表示可读的  router表示获取Vue实例上的一些功能函数
            }
        }
    }
</script>

<style scoped>

</style>