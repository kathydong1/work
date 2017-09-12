排序：
     var arr=[4,7,2,5,5,8,8,9,4,2]
     arr.sort(function(){
         return a-b(从小到大)    b-a(从大到小)   Math.random()-0.5(随机排序)
      })



ajax请求：
    异步的JS和XML，数据都是字符串，可以减少服务器压力，无刷新页面，优化用户体验，但缺点是不支持浏览器回退，安全性不好
    1.创建Ajax对象：new XMLHttpRequest()
    2.请求地址：Aja.open('get','文件地址+请求value')
                 post和get区别：
                     get:通过服务其的url发送给后端，安全性差，并且不能发送数据
                     post:通过send发送数据给后端，安全性好
               ajax.open('post','后端地址')
               ajax.setRequestHeader(Content-type,application/x-ww-form-)
               ajax.send(前端请求内容)
    3.发送请求：
           Ajax.send()
    4.服务求响应：
          Ajax.onload=function(){
             5.通话：Ajax.responseText()
          }
                     
