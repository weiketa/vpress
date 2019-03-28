---
title: checkbox多选框
---
# checkbox多选框
---
<xes-checkbox></xes-checkbox>

```js
<xes-checkbox 
:allData="allData" 
:pageNumber="index" 
:name="拖拽物" 
:filterKey="option"
:title=""
:index=""
@change="text($event)">
</xes-checkbox>
```
# Xes-checkbox Events
事件名称|说明|回调参数
:--|:--|:--
change|绑定值变化时触发的事件|选中的元素的componentName

# Xes-checkbox Attributes
参数        |说明                         |类型            |可选值|默认值
:---------  |:-------------------------- |:--             |:--  |:--
allData     |content.json配置⽂件整体数据 |json            |—     |—
pageNumber  |所在第几⼩题                 |number/string   |—	    |—
name        |组件显示名称                 |string          |—	    |—
conName     |组件属性名称                 |string          |—	    |—	
xkey        ||            |—     |—