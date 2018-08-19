# 18期 实战项目 vue接口文档



## 说明

### 移动端布局请看17期实战视频 

### 地图请看16期高德地图29节

### 天气预报参考17期易源API  第10节课

17期第24节课，APP打包

接口在18期的第7课



首先，安装cnpm i axios -S和cnpm i mint-ui -S和cnpm i less less-loader -D

接着，接着把相关的代码输入进去，
最后，在编译器里面输入npm run dev就可以打开页面了.



## 请求URL

​	http://47.96.29.109/vueProject/vue.php

## 请求method

​	get 

​	jsonp

## 参数部分



### 主页主标题

​	参数：	title=vueTitle

​	返回：	TZ-追梦-18期实战vue项目



### 主页轮播图部分

​	主页

​	参数：	title=banner

​	返回：	

``` js
[
    {"id":1,"picUrl":"http:\/\/47.96.29.109\/vueProject\/image\/banner\/1.jpg"},					{"id":2,"picUrl":"http:\/\/47.96.29.109\/vueProject\/image\/banner\/2.jpg"},					{"id":3,"picUrl":"http:\/\/47.96.29.109\/vueProject\/image\/banner\/3.jpg"},					{"id":4,"picUrl":"http:\/\/47.96.29.109\/vueProject\/image\/banner\/4.jpg"},					{"id":5,"picUrl":"http:\/\/47.96.29.109\/vueProject\/image\/banner\/5.jpg"}
]
```

​	内页

​	参数：title=banner + id

​	返回：

```js
{
    des:"2018年是“一带一路”国际合作高峰论坛举办一周年。2017年5月，论坛在北京的成功举办标志着共建“一带一路”倡议已经进入从理念到行动、从规划到实施的新阶段。“一带一路”倡议提出五年来，中国企业陆续走向海外，拓展国际市场，主持或承建了一大批基础设施项目。肯尼亚蒙内铁路、希腊比雷埃夫斯港、中巴经济走廊“两大”公路……这些项目都已有序推进或投入运营。如今，在“一带一路”沿线的“百花园”中，大批铁路、公路、港口、大桥和工业园区等基础设施项目都已破土动工，它们用中国智慧浇灌，绽放出鲜艳的花朵，焕发出勃勃生机，为改善沿线国家基础设施条件、带动当地经济社会发展发挥了积极作用。这是2017年7月6日俯拍的马尔代夫中马友谊大桥建设现场。中马友谊大桥于2016年初正式动工，是中马共建“一带一路”的重要合作项目。作为马尔代夫有史以来第一座大桥，同时也是印度洋上第一座跨海大桥，中马友谊大桥连通马尔代夫首都马累和机场岛，由桥梁、填海路堤及道路等组成，使用寿命100年。",
    picUrl:"http://47.96.29.109/vueProject/image/banner/banner1jpg",
    source:"新华网",
    title:"“一带一路”工程项目盘点"
}
```



###新闻列表

​	新闻列表页

​	参数：	title=newsList

​	返回：

```js
[
    {
        id: "1",
        title: "首艘国产航母将比辽宁舰更快形成初始作战能力",
        picUrl: "http://47.96.29.109/vueProject/image/newsList/1.jpg", time: "2018-05-14",
        source: "人民网"
    },
	{
        id: "2", 
        title: "不忘初心躬身强军实践 牢记使命传承红色血脉",
        picUrl: "http://47.96.29.109/vueProject/image/newsList/2.jpg",
        time: "2018-05-14",
        source: "环球网"
    },
    {…},
    {…}, 
    {…},
    {…},
    {…},
    {…},
    {…},
    {…}
]
```

​	新闻详细页

​	参数：	title=newsList + id

​	返回：	

```js
{
    content:"我国第二艘航母首次出海试验。据新华社消息，13日清晨，我国第二艘航母离开码头，开始海试。军事专家李杰在接受人民网采访时表示，航母海试将对动力、导航和雷达通信等系统进行测试，首次海试或需要数天时间。未来我国第二艘航母将比辽宁舰更快形成作战能力。首次海试或需数天时间据报道，这是中国第一艘国产航空母舰，也是中国的第二艘航母，于2013年11月开工，2017年4月26日正式出坞下水。下水以来，国产航母建造工作按计划稳步推进，完成了系统设备调试、舾装施工和相关系泊试验，具备了出海试验的技术条件。据李杰介绍，航母海试主要检测验证动力系统等设备的可靠性和稳定性，要在海上对航母的动力、导航、航海、雷达通信等系统进行实地检测，测试在不同气象条件下、不同海域中，航母各系统运转能否达到设计指标，同时还要测试航母的极限航行能力，如高速转弯等。首次海试所需时间较长，可能需要数天时间。 5月5日，一架直-18改进型直升机降落在其甲板上，随后起飞离开，这是国产航母首次起降直升机。李杰表示，除了直升机起降训练，此次航母海试期间还有可能进行固定翼舰载机的通场和触舰、着舰训练，以测试航母舰体是否能承受舰载机起降的巨大冲击力。首艘国产航母将更快形成初始作战能力前不久，辽宁舰航母编队连续跨越多个海区，分别在西太平洋、南海、东海等海域开展了实战化训练。军事专家杜文龙在接受央视采访时表示，这标志着辽宁舰已具备了初始作战能力。而这距离辽宁舰首次海试已经过去了近6年的时间。据李杰介绍，辽宁舰进行了10次左右的海试才完成所有测试步骤，首艘国产航母也要多次出海进行反复测试才能完成海试，这个过程需要半年到一年的时间。若一切顺利，今年年底或明年年初国产航母就可以交付部队。交付部队后，国产航母将展开大批量的训练，凭借在辽宁舰上积累的经验，首艘国产航母形成初始作战能力的时间应该比辽宁舰要短得多。李杰表示，若国产航母顺利经过海试的所有测试，达到了所有设计指标，说明国产航母是一件性能优良的武器，交付部队后，要经过大量的艰苦训练，才能真正“上阵杀敌”",
	picUrl:"http://47.96.29.109/vueProject/image/newsList/1.jpg",
	reporter:"邱越 芈金",
	source:"人民网",
	title:"首艘国产航母将比辽宁舰更快形成初始作战能力",
	titme:"2018年05月14日 16:45:13",
    责任编辑:"蔡琳琳"
}
```



### 图文分享	

​	女明星 男明星 全景图详情页共用一个模板

​	顶级导航

​	参数：	title=shareNav

​	返回：

```js
[
    {id: 1, title: "女明星", tip: 'womanStar'}
	{id: 2, title: "男明星",tip: 'manStar'}
	{id: 3, title: "全景图", tip: 'fullView'}
]
```

​	



女明星

参数：	title=womanStar

返回：

```js
[    
	{
        id: "1",
        picUrl: "http://47.96.29.109/vueProject/image/womanStar/1.gif",
        title: "赵丽颖，1987年10月16日出生于河北省廊坊市，中国内地影视女演员。",
        tip: "womanStar"
    },
 	{…},
    {…},
    {…}
]
```



男明星

参数：	title=manStar

返回：

```js
[
	{
        id: "1",
        picUrl: "http://47.96.29.109/vueProject/image/manStar/1.gif",
        title: "吴奇隆，1970年10月31日生于中国台湾省台北市，华语歌手、演员、制片人、出品人",
        tip: "manStar"
    },
    {…},
    {…},
    {…},
    {…},
    {…}, 
    {…}
]
```



全景图

参数：	title=fullView

返回：

```js
[
    {
        id: "1",
        picUrl: "http://47.96.29.109/vueProject/image/fullView/1.jpg",
        title: "全景图",
        tip: "fullView"
    },
    {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}
]
```



详情页：

​	参数：title = title + id

​	返回：

```js
 [{…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}]
```



### 商品展示

​	商品列表

​	参数：title=likeYou

​	返回：

```js
[
    {
        imgUrl: "http://47.96.29.109/vueProject/image/likeYou/1.jpg",
        des: "[为你推荐]日本 20cm 4L 加厚珐琅搪瓷加高汤锅 蒸锅 燃气电磁炉通用 包邮",
        symbol: "¥",
        price: "49",
        alreadyPaid: "256人付款"
    }, 
    {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}
]
```

​	

​	商品详情		

​		参数：title=title + index

```js
{
    alreadyPaid:"38人付款"
	des:"[为你推荐]日本产匠技 24-32CM 不粘平底锅 平底煎锅/炒锅 木柄"
	id:2
    imgUrl:"http://47.96.29.109/vueProject/image/likeYou/2.jpg"
	price:"458"
	symbol:"¥"
}
```













### 命令：

npm i mint-ui vue-preview axios vue-router moment vue -S;
npm i webpack html-webpack-plugin css-loader style-loader less less-loader postcss-loader babel-loader babel-core babel-preset-env babel-plugin-transform-runtime url-loader file-loader vue-loader vue-template-compiler webpack-dev-server -D



​	

```js
npm install --save less          // 本地按装less
npm install --save less-loader   // less模块的加载器，配合下面css-loader 和 style-loader
npm install --save css-loader    // css 模块加载器
npm install --save style-loader  // 以上两个插件的根基
npm install --save url-loader    // 用来处理 图片 字体 的模块，是由下面file-loader封装的。可自定义文件名
npm install --save file-loader  
npm install --save html-loader   // 加载html文件用的
npm install --save text-loader   // 加载纯文本用的
npm install --save html-webpack-plugin           // 生成html文件插件
npm install --save extract-text-webpack-plugin   // 单独提取css文件插件
npm install --save webpack                       // 提供webpack对象
npm install --save webpack-dev-server            // webpack-server开发包，方便调试
npm install --save vue
npm install --save jquery  
```

























































