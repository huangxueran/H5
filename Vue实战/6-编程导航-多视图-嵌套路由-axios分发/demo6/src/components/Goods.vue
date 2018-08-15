<!--<template>-->  1
<!--<div>-->
<!--<h2>商品页面</h2>-->
<!--</div>-->
<!--</template>-->

<!--<script>-->
<!--export default {-->
<!--name: "Goods"-->
<!--}-->
<!--</script>-->

<!--<style scoped>-->

<!--</style>-->

<!--<template> 2-->
    <!--<div>-->
        <!--<h2>商品页面</h2>-->
        <!--<button @click="prev">返回上一级</button>-->
        <!--<button @click="nav">编程导航</button>-->
    <!--</div>-->
<!--</template>-->

<!--<script>-->
    <!--export default {-->
        <!--methods: {-->
            <!--prev() {-->
                <!--this.$router.go(-1)-->
                <!--//route 表示可读的  router表示获取Vue实例上的一些功能函数-->
            <!--},-->
            <!--nav() {-->
                <!--this.$router.push({name: 'HelloWorld'})-->
            <!--}-->
        <!--}-->
    <!--}-->
<!--</script>-->

<!--<style scoped>-->

<!--</style>-->

<!--<template> 3-->
    <!--<div>-->
        <!--<h2>商品页面</h2>-->
        <!--<button @click="prev">返回上一级</button>-->
        <!--<button @click="nav">编程导航</button>-->
    <!--</div>-->
<!--</template>-->

<!--<script>-->
    <!--export default {-->
        <!--methods: {-->
            <!--prev() {-->
                <!--this.$router.go(-1)-->
                <!--//route 表示可读的  router表示获取Vue实例上的一些功能函数-->
            <!--},-->
            <!--nav() {-->
                <!--this.$router.push({name: 'HelloWorld'})-->
            <!--}-->
        <!--}-->
    <!--}-->
<!--</script>-->

<!--<style scoped>-->

<!--</style>-->

<template>
    <div>
        <h2>商品页面</h2>
        <button @click="prev">返回上一级</button>
        <button @click="nav">编程导航</button>
    </div>
</template>

<script>
    export default {
        methods: {
            prev() {
                this.$router.go(-1)
                //route 表示可读的  router表示获取Vue实例上的一些功能函数
            },
            nav() {
                this.$router.push({name: 'HelloWorld'})
            }
        }
    }
</script>

<style scoped>

</style>
