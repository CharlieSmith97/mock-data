### 这是我的项目[huawei-music](https://github.com/ProbeDream/huawei-music/)的模拟数据的repo

### 作者:ProbeDream

### 使用方法

    1.通过Ajax或者是fetch对提供的API进行请求操作

```js
fetch("https://ProbeDream.github.io/mock-data/resource/music-list.json")
  .then(() => {
    //TODO
  })
  .then(() => {
    //TODO
  });
```

```js
$.ajax({
　　　　url:"example URL",
　　　　type: 'get',
　　　　dataType: 'json',
　　　　contentType: "application/json; charset=utf-8",
　　　　data:detailDateStr,//json字符串
　　　　success: function(data){
　　　　if(data.result=="sucess"){
　　　　$.messager.alert('提示信息:', '保存成功', 'info',function(){
　　　　});
　　　　}else{
　　　　　　$.messager.alert('提示信息:', data.message, 'error');
　　　　}
　　});
```
### 提问:
> 有问题可以在[Issue](https://github.com/ProbeDream/mock-data/issues)提问

### 联系方式:
我的邮箱:Gump1016@163.com
