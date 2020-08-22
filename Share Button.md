### HTML Code:
##### Index.html
```HTML
<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
<meta charset="utf-8">
<title>Share Button</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="stylesheet" href="Style.css">
</head>
<body>
<div class="box">
<span> share  </span>
<div class="icon">
<i class="fa fa-github"></i>
<i class="fa fa-instagram"></i>
<i class="fa fa-whatsapp"></i>
<i class="fa fa-facebook-f"></i>
</div>
</div>
<div class="hide"> </div>
</body>
</html>
    
```
### CSS Code:
##### Style.css
```CSS
body{
  padding: 0;
  margin: 0;
  display:flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  height: 100vh;
  font-size: 70px;
  background-color: black;
  overflow: hidden;
}
.box{
  position: absolute;
  display: flex;
  background:none;
  height: 110px;
  overflow: hidden;
  width: 390px;
  border-radius: 55px;
  background-color: black;
}

span {
  position: absolute;
  background-color: white;
  color: black;
  padding: 20px;
    width: 350px;
  letter-spacing: 15px;
  border-radius: 80px;
  z-index: 99;
  transition: 1s;
}

.box:hover span{
  transition: 1s;
  transform: translateX(-400px);
}
.icon {
  position: absolute;
  background-color: #121212;
  color: white;
  padding: 20px;
  width: 350px;
  letter-spacing: 5px;
  border-radius: 80px;

  }
i{
  transform: scale(0.1);
  font-size: 12px;
  transition: .25s;
  opacity: 0;
  cursor: pointer;
}
.box:hover i{
  opacity: 1;
    transform: scale(1);
}
.box:hover i:nth-child(1)
{
  transition-delay: 0.4s;

}
.box:hover i:nth-child(2)
{
  transition-delay: 0.3s;

}
.box:hover i:nth-child(3)
{
  transition-delay: 0.2s;

}
.box:hover i:nth-child(4)
{
  transition-delay: 0.1s;
  }

```
