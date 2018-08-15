<!--<template> 3-->
        <!--<div>-->
            <!--<h2>主体内容</h2>-->
        <!--</div>-->
<!--</template>-->

<!--<script>-->
    <!--export default {-->

    <!--}-->
<!--</script>-->

<!--<style>-->

<!--</style>-->

<!--<template> 4-->
    <!--<div>-->
        <!--<h2>主体内容</h2>-->
        <!--<router-link :to="{name:'phone'}">手机类目</router-link>-->
        <!--<router-view class="phone"></router-view>-->
    <!--</div>-->
<!--</template>-->

<!--<script>-->
    <!--export default {-->

    <!--}-->
<!--</script>-->

<!--<style>-->

<!--</style>-->

<!--<template> 5-->
    <!--<div>-->
        <!--<h2>主体内容</h2>-->
        <!--<router-link :to="{name:'phone'}">手机类目</router-link>-->
        <!--<router-view class="phone"></router-view>-->
      <!--<hr>-->
      <!--<ol>-->
        <!--<li v-for="(item,index) in banner" :key="index">-->
          <!--<img :src="item.picUrl" width="200" alt="">-->
        <!--</li>-->
      <!--</ol>-->
      <!--<hr>-->
    <!--</div>-->
<!--</template>-->

<!--<script>-->
    <!--export default {-->
      <!--data(){-->
        <!--return{-->
          <!--banner:[]-->
        <!--}-->
      <!--},-->
      <!--created(){-->
         <!--this.$.get('http://47.97.223.104:6341/users')-->
              <!--.then((res)=>{-->
                  <!--//console.log( JSON.parse(res) )-->
              <!--});-->

        <!--this.$ajax.get('http://47.96.29.109/vueProject/vue.php?title=banner')-->
             <!--.then((res)=>{-->
                 <!--console.log( res.data );-->
                 <!--this.banner = res.data-->
             <!--})-->
      <!--}-->
    <!--}-->
<!--</script>-->

<!--<style>-->

<!--</style>-->

<!--<template> 6-->
  <!--<div>-->
    <!--<h2>主体内容</h2>-->
    <!--<router-link :to="{name:'phone'}">手机类目</router-link>-->
    <!--<router-view class="phone"></router-view>-->
    <!--<hr>-->
    <!--<ol>-->
      <!--<li v-for="(item,index) in banner" :key="index">-->
        <!--<img :src="item.picUrl" width="200" alt="">-->
      <!--</li>-->
    <!--</ol>-->
    <!--<hr>-->
  <!--</div>-->
<!--</template>-->

<!--<script>-->
  <!--export default {-->
    <!--data(){-->
      <!--return{-->
        <!--banner:[]-->
      <!--}-->
    <!--},-->
    <!--created(){-->
      <!--this.$.get('http://47.97.223.104:6341/users')-->
        <!--.then((res)=>{-->
        <!--});-->

      <!--this.$ajax.get('http://47.96.29.109/vueProject/vue.php?title=banner')-->
        <!--.then((res)=>{-->
          <!--this.banner=res.data-->
        <!--})-->
    <!--}-->
  <!--}-->
<!--</script>-->

<!--<style scoped>-->
   <!--/*scoped局部的*/-->
    <!--ol{-->
      <!--width: 600px;-->
    <!--}-->
    <!--ol li{-->
      <!--float: left;-->
    <!--}-->
<!--</style>-->

<!--<template> 7-->
  <!--<div>-->
    <!--<h2>主体内容</h2>-->
    <!--<router-link :to="{name:'phone'}">手机类目</router-link>-->
    <!--<router-view class="phone"></router-view>-->
    <!--<hr>-->
    <!--<ol>-->
      <!--<li v-for="(item,index) in banner" :key="index">-->
        <!--<img :src="item.picUrl" width="200" alt="">-->
      <!--</li>-->
    <!--</ol>-->
    <!--<hr>-->
      <!--<button @click="send">发起请求</button>-->
    <!--<hr>-->
  <!--</div>-->
<!--</template>-->

<!--<script>-->
  <!--export default {-->
    <!--data(){-->
      <!--return{-->
        <!--banner:[]-->
      <!--}-->
    <!--},-->
    <!--methods:{-->
      <!--send(){-->
        <!--let php='vue.php';-->
        <!--let title='banner1';-->
        <!--let url=php + '?title='+title-->

        <!--this.$ajax.get('http://47.96.29.109/vueProject/'+url)-->
          <!--.then((res)=>{-->
            <!--console.log(res.data)-->
          <!--})-->
      <!--}-->
    <!--},-->
    <!--created(){-->
      <!--this.$.get('http://47.97.223.104:6341/users')-->
        <!--.then((res)=>{-->
        <!--});-->
      <!--this.$ajax.get('http://47.96.29.109/vueProject/vue.php?title=banner')-->
        <!--.then((res)=>{-->
          <!--this.banner=res.data-->
        <!--})-->
    <!--}-->
  <!--}-->
<!--</script>-->

<!--<style scoped>-->
  <!--/*scoped局部的*/-->
  <!--ol{-->
    <!--width: 600px;-->
  <!--}-->
  <!--ol li{-->
    <!--float: left;-->
  <!--}-->
<!--</style>-->

<!--分发-->
<!--<template> 8-->
  <!--<div>-->
    <!--<h2>主体内容</h2>-->
    <!--<router-link :to="{name:'phone'}">手机类目</router-link>-->
    <!--<router-view class="phone"></router-view>-->
    <!--<hr>-->
    <!--<ol>-->
      <!--<li v-for="(item,index) in banner" :key="index">-->
        <!--<img :src="item.picUrl" width="200" alt="">-->
      <!--</li>-->
    <!--</ol>-->
    <!--<hr>-->
    <!--<button @click="send">发起请求</button>-->
    <!--<hr>-->
  <!--</div>-->
<!--</template>-->

<!--<script>-->
  <!--export default {-->
    <!--data(){-->
      <!--return{-->
        <!--banner:[]-->
      <!--}-->
    <!--},-->
    <!--methods:{-->
      <!--send(){-->
        <!--let php='vue.php';-->
        <!--let title='banner1';-->
        <!--let url=php + '?title='+title-->

        <!--this.$ajax.all([-->
          <!--this.$ajax.get('http://47.96.29.109/vueProject/vue.php?title=banner1'),-->
          <!--this.$ajax.get('http://47.96.29.109/vueProject/vue.php?title=banner2'),-->
          <!--this.$ajax.get('http://47.96.29.109/vueProject/vue.php?title=banner3'),-->
        <!--])-->
          <!--.then(this.$ajax.spread((res1,res2,res3)=>{-->
            <!--console.log(res1.data)-->
            <!--console.log(res2.data)-->
            <!--console.log(res3.data)-->
          <!--}))-->
          <!--.catch((err)=>{-->
            <!--console.log(err)-->
          <!--})-->
      <!--}-->
    <!--},-->
    <!--created(){-->
      <!--this.$.get('http://47.97.223.104:6341/users')-->
        <!--.then((res)=>{-->
        <!--});-->
      <!--this.$ajax.get('http://47.96.29.109/vueProject/vue.php?title=banner')-->
        <!--.then((res)=>{-->
          <!--this.banner=res.data-->
        <!--})-->
    <!--}-->
  <!--}-->
<!--</script>-->

<!--<style scoped>-->
  <!--/*scoped局部的*/-->
  <!--ol{-->
    <!--width: 600px;-->
  <!--}-->
  <!--ol li{-->
    <!--float: left;-->
  <!--}-->
<!--</style>-->

<!--<template>  9-->
  <!--<div>-->
    <!--<h2>主体内容</h2>-->
    <!--<router-link :to="{name:'phone'}">手机类目</router-link>-->
    <!--<router-view class="phone"></router-view>-->
    <!--<hr>-->
    <!--<ol>-->
      <!--<li v-for="(item,index) in banner" :key="index">-->
        <!--<img :src="item.picUrl" width="200" alt="">-->
      <!--</li>-->
    <!--</ol>-->
    <!--<hr>-->
    <!--<button @click="send">发起请求</button>-->
    <!--<hr>-->
  <!--</div>-->
<!--</template>-->

<!--<script>-->
  <!--export default {-->
    <!--data(){-->
      <!--return{-->
        <!--banner:[]-->
      <!--}-->
    <!--},-->
    <!--methods:{-->
      <!--send(){-->
        <!--let php='vue.php';-->
        <!--let title='banner1';-->
        <!--let url=php + '?title='+title-->

        <!--this.$ajax.all([-->
          <!--this.$ajax.get('http://47.96.29.109/vueProject/vue.php?title=banner1'),-->
          <!--this.$ajax.get('http://47.96.29.109/vueProject/vue.php?title=banner2'),-->
          <!--this.$ajax.get('http://47.96.29.109/vueProject/vue.php?title=banner3'),-->
        <!--])-->
          <!--.then(this.$ajax.spread((res1,res2,res3)=>{-->
            <!--console.log(res1)-->
            <!--console.log(res2)-->
            <!--console.log(res3)-->
          <!--}))-->
          <!--.catch((err)=>{-->
            <!--console.log(err)-->
          <!--})-->
      <!--}-->
    <!--},-->
    <!--created(){-->
      <!--this.$.get('http://47.97.223.104:6341/users')-->
        <!--.then((res)=>{-->
        <!--});-->
      <!--this.$ajax.get('http://47.96.29.109/vueProject/vue.php?title=banner')-->
        <!--.then((res)=>{-->
          <!--this.banner=res.data-->
        <!--})-->
    <!--}-->
  <!--}-->
<!--</script>-->

<!--<style scoped>-->
  <!--/*scoped局部的*/-->
  <!--ol{-->
    <!--width: 600px;-->
  <!--}-->
  <!--ol li{-->
    <!--float: left;-->
  <!--}-->
<!--</style>-->

<template>
  <div>
    <h2>主体内容</h2>
    <router-link :to="{name:'phone'}">手机类目</router-link>
    <router-view class="phone"></router-view>
    <hr>
    <ol>
      <li v-for="(item,index) in banner" :key="index">
        <img :src="item.picUrl" width="200" alt="">
      </li>
    </ol>
    <hr>
    <button @click="send">发起请求</button>
    <hr>
  </div>
</template>

<script>
  export default {
    data(){
      return{
        banner:[]
      }
    },
    methods:{
      send(){
        let php='vue.php';
        let title='banner1';
        let url=php + '?title='+title

        this.$ajax.all([
          this.$ajax.get('vue.php?title=banner1'),
          this.$ajax.get('vue.php?title=banner2'),
          this.$ajax.get('vue.php?title=banner3'),
        ])
          .then(this.$ajax.spread((res1,res2,res3)=>{
            console.log(res1.data)
            console.log(res2.data)
            console.log(res3.data)
          }))
          .catch((err)=>{
            console.log(err)
          })
      }
    },
    created(){
      this.$.get('http://47.97.223.104:6341/users')
        .then((res)=>{
        });
      this.$ajax.get('http://47.96.29.109/vueProject/vue.php?title=banner')
        .then((res)=>{
          this.banner=res.data
        })
    }
  }
</script>

<style scoped>
  /*scoped局部的*/
  ol{
    width: 600px;
  }
  ol li{
    float: left;
  }
</style>
