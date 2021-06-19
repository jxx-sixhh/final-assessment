@[TOC](小明商城---考核项目说明)
# 1.项目概述
项目名称：小明商场
项目描述：样式仿照小米商城制作的电商网站。包括首页、服务页、购物车页。
## 1.1.目的
1.1.掌握pc端网页开发流程及布局思路
1.2.掌握利用“媒体查询”实现响应式布局
1.3.复习学过的h5、c3、jQuery、bootstrap框架等知识。
## 1.2.布局设计
### 各页面介绍
由于笔者艺术细胞实在不强，难以设计出一个比较好看的网页，故选择了参考小米商城的主页。另外在首页部分加设了响应式设计。

**首页布局为**
|说明|类名|
|--|--|
| 第一个导航栏 | first-header (nav) |
| 第二个导航栏 |second-header (nav)  |
|轮播图部分|swiper|
|秒杀板块|seckill|
 |手机展示模块|phone|
 |家电展示模块|home|
 |智能展示模块|smart|
|底部|footer|
> 小米商城主页有好几个这样的版块，不过他们的样式都是相同的，因为已经掌握了怎么做，我就只写了一个phone模块，然后复制出了home和smart模块。

**service 服务页**
导航栏及底部部分同主页
|说明|类名|
|--|--|
| 第一个导航栏 | first-header (nav) |
| 第二个导航栏 |second-header (nav)  |
|轮播图部分|swiper|
|展示部分1|service1|
|展示部分2|service2|
|tab栏搜索部分|tab|
|底部|footer|

**shopcar购物车页** 
导航栏及底部部分同主页
|说明|类名|
|--|--|
| 第一个导航栏 | first-header (nav) |
| 第二个导航栏 |second-header (nav)  |
|购物车|cart-wrap|
|底部|footer|
### 响应式设计
首页面在利用bootstrap框架的基础上，利用媒体查询，实现了响应式设计。可以实现首页面各个版块的布局随着窗口的大小改变，不影响正常观看。因此在手机端也能正常观看.(由于时间不是很够，所以只制作了首页的响应式，不太完美).
## 1.3.网站优化三大标签

```html
<!-- 三大标签 -->
    <!-- 网页title 标题 -->
    <title>小明商城-综合网购首选-正品低价、品质保障、配送及时、轻松购物！</title>
    <!-- Description 网站说明 -->
    <meta name="description" content="小明商城直营小米公司旗下所有产品，囊括小米手机系列小米MIX、小米Note 2，红米手机系列红米Note 4、红米4，智能硬件，配件及小米生活周边，同时提供小米客户服务及售后支持。" />
    <!-- keywords关键字 -->
    <meta name="keywords" content="小米,小米6,红米Note4,小米MIX,小米商城" />
```
## 1.4.开发工具
Visual Studio Code,主流浏览器（以egde浏览器为主）
## 1.5.技术栈

 - HTML5
 - CSS3
 - Less
 - Bootstrap框架
 - JQuery
 - swiper插件
 - IcoMoon字体库

# 2.代码规范
## 2.1命名规范
ClassName的命名尽量趋于精短、且意义准确、易区分。
单词之间采用"-"连接。(回顾以前的远古笔记，发现貌似更应该使用"_"连接，以后一定改正)
例如首页的秒杀部分，设置class="seckill".
手机展示栏部分，设置class="phone".

## 2.2属性书写顺序规范
less书写时遵循了以下顺序

 1. 定位属性：display  position  float  left  top  right  bottom   overflow  clear   z-index
2. 自身属性：width  height  padding  border  margin   background
3. 文字样式：font-family   font-size   font-style   font-weight   font-varient   color    
 4. 文本属性：text-align   vertical-align   text-wrap   text-transform  text-indent    text-decoration   letter-spacing    word-spacing    white-space   text-overflow
5. css3中新增属性：content   box-shadow   border-radius  transform……
# 3.功能说明
搞个ppt

