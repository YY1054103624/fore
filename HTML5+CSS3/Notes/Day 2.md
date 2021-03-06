# 基本元素

## html元素

* W3C标准建议为html元素增加一个lang属性，作用是：
    * 帮助语音合成工具确定要使用的发音
    * 帮助翻译工具确定要使用的翻译规则

## head元素

* title元素
* meta元素
* style
* link
    * 可以引入外部css
* base
* script
* noscript

## 字符编码

* 作用：将文字存储在计算机中，之后解析出来显示
* 应用：所有的网页目前都采用utf-8编码，<meta charset="gbk">表示浏览器使用gbk进行解码

## h、p、strong元素

## h元素和SEO

* h元素有助于网站的SEO（Search Engine Optimization）优化，可以促进关键词排名
* 百度搜索实际上是爬虫，优先匹配h1标签
* 建议在网页中最多只有一个h1元素
* 乱用h元素不仅不会给网站带来好的权重，同时也有可能被搜索引擎认为作弊，最后导致k站

## code、br、hr元素

* 被code标签包裹的字体是等宽字体
* br换行
* hr分割线

## 字符实体

* &nbsp;空格，可以使用test-indent代替
* &lt;小于
* &gt;大于
* &amp;&
* &quot;"
* &apos;'

## span元素

* span元素
    * 默认情况下，跟普通文本几乎没有差别
    * 用于区分特殊文本和普通文本，比如用来显示一些关键字

## div元素

## img元素

* img元素专门用来显示图片
  * 注意：img元素是单标签
  * 在HTML5规范中，alt是img元素的必要属性

## 常用图片格式

* web中常用的图片格式有
* png：静态图片，支持透明
* jpg：静态图片，不支持透明（jpeg）
* gif：动态图片、静态图片，支持透明

## 像素

* 像素（px）是图像显示的最小单位

## a元素

* href
* target
  * _self
  * _blank
  * _parent
  * _top