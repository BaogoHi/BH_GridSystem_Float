# 基于float的栅格系统
>使用float完成
,分成12份一行

## 代码基本结构
```html
<div class="grid">
  <div class="col-bg-1">
    <div class="col"></div>
  </div>
</div>
```

## 分割类型

<table border="1">
  <tr>
    <th>width>=960px</th>
    <th>960px>width>640px</th>
    <th>640px>width>320px</th>
  </tr>
  <tr>
    <td>col-bg-*</td>
    <td>col-md-*</td>
    <td>col-sm-*</td>
  </tr>
</table>

