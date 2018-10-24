# 使用文档

## 简介

**ng-carousel** —— 基于angular的图片轮播组件，使用简单，配置方便，提供多属性设置灵活性高。

+ 官网：暂无
+ 文档：https://mrfujianfei.github.io/ngx-carousel-ts.github.io/
+ 源码：https://github.com/Mrfujianfei/ng-carousel

*目前还在开发持续开发中*

## 安装和下载

#### npm：

 `npm i ngx-carousel-ts`

## 快速使用

**1.步骤一**：引入NgxCarouselTsModule。

 `import { NgxCarouselTsModule } from 'ngx-carousel-ts';`

**2.步骤二**：在app.module里面声明NgxCarouselTsModule。

 `imports: [ NgxCarouselTsModule ]`

**3.步骤三**：使用。

HTML如下：

 `<ngx-carousel [options]="options"></ngx-carousel>`

Typescipte如下：

```
export class AppComponent {
    options = {
        data:['图片路径1','图片路径2'],
    };
}
```

*注：图片路径可以是相对路径，也可以是绝对路径！*


## 属性配置列表

属性名|说明|类型|默认值
---|---------|---|---
**width**|轮播容器宽度|<font color=#FF0000 >number</font>|900
**height**|轮播容器高度|<font color=#FF0000 >number</font>|300
**data**|数据源|<font color=#FF0000 >array</font>|[]
**showHandover**|是否显示左右切换图标|<font color=#FF0000 >boolean</font>|true
**handoverPosition**|左右切换图标的位置|<font color=#FF0000 >string</font>|'inner' &#124; 'side' 
**fmAlign**|图片在容器内的对齐方式|<font color=#FF0000 >string</font>|'center' &#124; 'start' &#124; 'end'
**showDottedMenu**|是否展示底部导航|<font color=#FF0000 >boolean</font>|true


## 交流 & 提问

- github：https://github.com/Mrfujianfei/ng-carousel/issues
- QQ：1501324336
- WeChat：fu1501324336

## 关于作者

作者：喜欢的话点个star吧，谢谢鼓励！

