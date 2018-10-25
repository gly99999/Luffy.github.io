<!DOCTYPE>
<html>
<head>
    <meta charst="utf-8">
    <title>滑动门</title>
   <style>
       .div1{
           background-repeat: repeat-x;
           background-image:url("../image/滑动门.png");
           margin-top: 200px;
            height: 50px;
       }
       *{
           margin: 0;
           padding: 0;
       }
       .div1:hover .div3{

           display: block;
       }
       .div3{
           background-repeat: repeat-x;
          background-image: url("../image/滑动门.png");
           background-size: 200px;
           display: none;
           padding-top: 10px;
           height:200px;
           margin-top: 22px;
           margin-left: 515px;
       }
       .div2{
           padding-top: 10px;
           text-align: center;
       }
        img{
            margin-left: 60px;
            width: 150px;
            height: 180px;
        }
      p{
           margin-left: 50px;
       }
       pre{
           margin-left: 90px;
       }
   </style>
</head>
<body>
<div class="div1">
        <div class="div2">课程中心</div>
        <div  class="div3">
            <img src="../image/热吧1.jpg">
            <img src="../image/热吧2.jpg">
            <img src="../image/热吧3.jpg">
            <img src="../image/热吧4.jpg"><br>
            <pre>    热吧                              热吧                              热吧                              热吧</pre>
        </div>
</div>

</body>
</html>
