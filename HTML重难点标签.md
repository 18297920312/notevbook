# HTML重难点标签
## a 标签的用法
* 作用：表示一个超链接
* 属性： 
```h
1.href="//google.com"  表示链接的地址
  href="javascript:alert();" 点击链接后执行相应js代码
  href="javascript:;" 点击链接后浏览器不会由任何操作
  href="#" 点击链接后浏览器会刷新页面
  href="#id名称" 点击链接后浏览器会跳转到id所在那一行
  href="mailto:邮箱地址" 点击后发邮件到该地址
  href="tel:电话号码" 点击后拨打相应号码电话

2.target="_blanke"  表示在新窗口打开
         "_self"    表示在当前页面切换

3.download 表示这是一个下载链接         
```
## table 标签
* 作用：制作一个表格
* 一般要有 thead、tbody、tfoot
  ```html
  <table>
        <thead>
            <th> </th>
            <th> </th>
            <th> </th>
        </thead>
        <tbody>
            <th> </th>
            <td> </td>
            <td> </td>
        </tbody>
        <tfoot>
            <th> </th>
            <td> </td>
            <td> </td>
        </tfoot>
  </table>
  ```
* 属性：
  ```h
  1.table-layout:auto 调整表格每一列每个单元的大小，根据每个单元格的字数，每一列的宽度是不同的
    table-layout:fixed 调整表格每个单元的大小，每一列的宽度是相同的

  2.border-spacing: 10px 调整每个单元格之间的间距

  3.table-collapse:collapse 消除单元格的间距
  ````
## img 标签
* 作用：发出一个get请求下载图片
* 属性：
```html
  1.alt="文字" 当图片加载失败时显示这里的文字

  2.height="10px"
    width="10px"
  切记：不能改变图片的长宽比是前端程序员的底线,一般情况下只写图片的宽度或者高度

  3.src="图片的路径" 
```
* 事件： 
  onload 图片加载成功的事件
  onerror 图片加载失败的事件

* 响应式布局：
```max-width:100% 宽度就会随着屏幕的大小而改变 ```

## 打开html文件的方法
* parcel 文件路径
* http-server -c -1