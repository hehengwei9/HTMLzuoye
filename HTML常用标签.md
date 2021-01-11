# 《HTML常用标签》
* a 标签的用法？

  答：
  ````HTML
     <p><a herf="网址" target="不把网址在新页面打开">内容</a></p>

       <p><a herf="网址" download="下载页面起名字">内容</a></p>
  ````
* img标签的用法？

  答：
  ```
  <img src="图片网址/图片路径" alt="当图片加载不出来的时候显示的信息>

  <img src="图片网址/图片路径" height=高度 width=宽度>

  ```

* table标签的用法？

  答：thead--表头
      tbody--表身
      tfoot表尾
      th--每列的项目
      tr--行
      td--列
  ```
  <table>
  <thead><tr><th>内容<th>
         </tr>
  </thead><tr><td>内容</td>
         </tr>
  <tbody>
  </tbody><tr><td>内容</td>
         </tr>
  <tfoot>
  </tfoot>
  </table>
  ```
* 其他感想

  答：input中的type类型着重要理解，table标签的
  ```
      <table>
      <thead><tr><th>内容<th>
         </tr>
      </thead><tr><td>内容</td>
         </tr>
      <tbody>
        <tr>
        <td>内容</td>
       </tr>
      </tbody>
      
      <tfoot>
        <tr>
        <td>内容</td>
        </tr>
      </tfoot>
      </table>
    ```  