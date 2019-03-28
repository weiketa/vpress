---
title: select选择器
---
# select选择器 
---
<xes-select></xes-select>
```js
<xes-select
 :allData="allData" 
 :pageNumber="index" 
 :filterKey="option" 
 :name="拖拽物" 
 :label="拖拽物" 
 ref="optionSelect"
 @change="text($event)">
 </xes-select>
```
# Xes-select Events
事件名称|说明|回调参数
:--|:--|:--
change|绑定值变化时触发的事件|选中的元素的componentName

# Xes-select Attributes
参数      |说明                         |类型            |可选值|默认值
:---------|:-------------------------- |:--             |:--  |:--
allData   |content.json配置⽂件整体数据 |json            |—     |—
pageNumber|所在第几⼩题                 |number/string   |—	    |—
filterKey |该组件所需数据源关键值        |string          |—	   |—	
label     |Select下拉框名称             |string          |—	    |—	
name      |组件名称                     |string          |—	    |—	