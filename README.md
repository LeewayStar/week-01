## 完成说明
week-01 已完成

第一周的作业主要是对给定的demo进行练习，利用已经学习的html和css进行目标为practice.jpg的界面代码的编写，目的是进一步的巩固已学知识和为下一次课做好准备

## 编写流程
- 该界面分为基本`html`的`head`和`body`部分，以及相应的`css`部分

**确定颜色和字体:**

1.整体的`page`:
> `字体`:
> 
	-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;

> `颜色`:
> 
	color: #eee

**在`body`部分确定标题的导航栏颜色:**

2.头部`header`的top,top-title,等一系列
> `配色`分别为:
> 
> top; top-title
> 
	rgba(235, 15, 15, 0.89);
    color:#fff

>.tabs > ul; .tab-item; .tab-active
>
    background-color: #cd2523;
    color: #fff
>.cats; .cat-active
>
    color:#fff;
	background-color: #d23e34
    color: #fff

3.身体`main`的row;.comment;.comment strong
>
	background-color: #fff;
	color: #666;
	color: #333;
***
**逻辑分段**
>`head`是由'！'和'ENTER键'构成，将语言更改为"zh-CN"

> `body`部分由一个"page"构成;
> "page"分为 'header' 和 'main' 两个部分，
> 
>> header 部分主要是显示从排行榜到文章的设计，而 main 则展现三个板块的内容
>> header 是由3个导航栏部分组成的：
> 
>>> top-title 排行榜；
> 
>>> tabs 两个带有图片的字段；
> 
>>> 另外一个是 cats 的文本字段

>> main是由3个row部分组成，
>>> 每一个row都由一个 content 和 comment 组成;
> 
>>> content包含(标签和图片)，comment包含评价内容和两张图标;(评论和点赞）

## 完成过程所遇到的问题

1. 刚开始觉得要一个个的敲特别麻烦,想有没有html的基础模板,经过网上的查询,发现直接用!就可以生成基本模板.

2. 在分析老师给定的demo时,逐渐学会分析html代码的逻辑,发现和面向对象的类的概念类似,逐渐理解html编写的逻辑,慢慢分解,自己确定什么是父容器,什么部分继承,存在几层嵌套等.

3. 在遇到评论和点赞的图片问题时:由于没有理解老师给定的那个fonts文件夹内的icons.woff2文件的含义,导致在页面运行时显示不出来相对应的图标,后来经过请教同学发现必须导入到项目内才能呈现出效果.

4. 在设置图片大小时,总是不满意比例,后面经网上查询,发现可以设置相对布局:'max-height: 25vw;'width采用百分比的方式解决问题.






