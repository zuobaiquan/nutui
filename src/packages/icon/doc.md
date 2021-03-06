# Icon 图标

## 基本用法

```html
<nut-icon 
  type="top"
>
</nut-icon>
```
## 自定义尺寸

支持通过**size**设置图标大小，注意包含单位，如“40px”、“4rem”…

```html
<nut-icon 
  type="action" 
  size="40px"
>
</nut-icon>
```

## 自定义颜色

支持通过**color**设置图标颜色，支持十六进制/RGB/RGBA等写法。

```html
<nut-icon 
  type="trolley" 
  color="#f0250f"
>
</nut-icon>
```
## 自定义svg图标

支持通过**url**可以自定义添加额外的图片。

```html
<nut-icon type="self" :url="require('../../assets/svg/trolley.svg')"></nut-icon>
```
## type可选值

nutui 自带图标库提供了下面的这些可选值。

* top
* down
* right
* action
* more
* trolley
* search
* tick
* plus
* minus
* cross
* circle-cross


## Prop

| 字段 | 说明 | 类型 | 默认值
|----- | ----- | ----- | ----- 
| type | 图标，可选值top/action/cross/down/right/more/plus/search/trolley/tick/minus/circle-cross | String | -
| size | 尺寸，需要带单位 | String | -
| color | 颜色 | String | -
| url | 自定义图标路径，必须是svg格式,请用 require 方式引入 | String | - 