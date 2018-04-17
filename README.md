<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>我的项目</title>
</head>
<style>
body{
    background-color: #fff2e3;
    font-size: 14px;
    text-align: center;
    font-family: "Lantinghei SC", "Open Sans", Arial, "Hiragino Sans GB", "Microsoft YaHei", "\5FAE\8F6F\96C5\9ED1", "STHeiti", "WenQuanYi Micro Hei", SimSun, sans-serif;
    color: #87968e;
    }
body,p,span,a,{
    margin: 0;
    padding: 0;
}
.picture{
      width: 800px;
      margin: 0 auto;
}

.xm p{
    display: inline-block;
}
.mg p{
    display: inline-block;
}
.btn{
    margin: 3px;
    padding: 6px 14px;
    font-weight: normal;
    border-radius: 2px;
    background: #72b890;
    color: #fff;
    text-decoration: none;
}
.xm{
    margin: 40px 0;
}
.mg{
    margin: 30px 0;
}
h1{
    font-size: 42px;
} 
.introduction{opacity: 0.6;
    margin-top: 10px;
}
#aaa{ text-decoration: none;
color: #72b890;
}
.btn:hover{
  opacity: 0.8;
}
.active{
  opacity: 0.6;
}
</style>
<body>
    <div class="up">
    <h1>我的项目</h1>
    <P class="introduction">一句话项目介绍</P>
     </div>
    <div class="xm">
    <p><a href="#" class="btn active">项目1</a></p>
    <p><a href="#" class="btn">项目2</a></p>
    <p><a href="#" class="btn">项目3</a></p>
    <p><a href="#" class="btn">项目4</a></p>
    <p><a href="#" class="btn">项目5</a></p>
    </div>
    <div class="picture">
    <img src="http://7xpvnv.com2.z0.glb.qiniucdn.com/65d4aba2-a097-4b24-aaa0-ebbaf7eedab2" alt="">
    </div>
    <div class="mg">
    <p><a href="#" class="btn">查看源码</a></p>
    <p><a href="#" class="btn">使用说明</a></p>
    </div>
    <div class="author">
     <span>作者：</span><a href="#" id="aaa">我</a>
    </div>
    
</body>
</html>