---
title: 图片上传器
---
# 图片上传器
---
<xes-upload-image></xes-upload-image>

```js
<xes-upload-image 
:allData="allData" 
:resourceData="resourceData" 
:pageNumber="index"  
:name="目标区域" 
:conName = "option1"  
@updateResourceData = updateResourceData>
</xes-upload-image>
```
# Xes-upload-image Events
事件名称|说明|回调参数
:--|:--|:--
updateResourceData|刷新资源数据|—

# Xes-upload-image Attributes
参数        |说明                         |类型            |可选值|默认值
:---------  |:-------------------------- |:--             |:--  |:--
allData     |content.json配置⽂件整体数据 |json            |—     |—
resourceData|resource.json配置⽂件资源数据|json            |—     |—
pageNumber  |所在第几⼩题                 |number/string   |—	    |—
name        |组件显示名称                 |string          |—	    |—
conName     |组件属性名称                 |string          |—	    |—	