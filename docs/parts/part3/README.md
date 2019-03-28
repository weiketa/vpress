---
title: radio单选框
---
# radio单选框
---
<xes-radio></xes-radio>

```js
<xes-radio  
:name="['图片','动画','精灵序列图']"  
@change="text($event)">
</xes-radio>
```
# Xes-radio Events
事件名称|说明|回调参数
:--|:--|:--
change|绑定值变化时触发的事件|选中的元素的componentName

# Xes-radio Attributes
参数        |说明                         |类型            |可选值|默认值
:---------  |:-------------------------- |:--             |:--  |:--
name        |组件显示名称                 |array           |—	    |—