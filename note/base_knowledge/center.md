# 居中布局

## 三 居中布局 20180729
> [测试用例](https://github.com/wanwusangzhi/WebStudy/blob/master/dayTest/commonTest/center.html)

```
<!DOCTYPE html>
<html>
<head>
    <title>center container</title>
</head>
<style type="text/css">
.wrapper {
    position: relative;
    width: 500px;
    height: 500px;
    border: 1px solid red; 
 }
.content{
    position: absolute;
    width: 200px;
    height: 200px;
    /*top、bottom、left和right 均设置为0*/
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    /*margin设置为auto*/
    margin:auto;
    border: 1px solid green;    
} 
</style>
<body>
<div class="wrapper">
     <div class="content"></div>
</div>
</body>
</html>
```