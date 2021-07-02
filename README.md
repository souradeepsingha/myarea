
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
    margin: 0;
    padding: 0;
}
body{
   background-image: url('https://thumbs.dreamstime.com/b/musical-notes-5034873.jpg' );
}
.header-menu {
    background: #db34c5;
    border-radius: 10px;
    margin: 12px 23px;
}
.header-menu ul {
    text-align: center;
}
.header-menu ul li {
    display: inline-block;
    margin-left: -4px;
}
.header-menu ul li a {
    color: #fff;
    padding: 15px 40px;
    display: inline-block;
    font-size: 20px;
    text-decoration: none;
    border-right: 1px solid #ddd;
}
.header-menu ul li:first-child a{
    border-left: 1px solid #ddd;
}
.header-menu ul li:hover > a{
    background: #c015d6;
}

/*  DropDOnw Mneu Start  */
.header-menu ul li{
    position: relative;
    border-radius: 23px;
}
.header-menu ul li ul{
    position: absolute;
    left: 0;
    top: 100%;
    width: 300px;
    background-color: #ffd102;
    border-top: 1px solid #ddd;
    border-radius: 8px;
    transition: .1s;
}
.header-menu ul li ul li{
    display: block;
    margin-left: 0;
}
.header-menu ul li ul li a{
    display: block;
    border: none;
    border-bottom: 1px solid #ddd;
}
.header-menu ul ul li:first-child a{
    border-left: none;
}

/* Hover part */
.header-menu ul li ul{
    opacity: 0;
    visibility: hidden;

    transform: scaleY(0);
    transform-origin: top center;
}
.header-menu ul li:hover ul{
    transform: scaleY(1);
    opacity: 1;
    visibility: visible;
}

.header-menu ul li ul li a:hover{}


 /* Social Menu  */
.socialMenu{
    margin-top: 100px;
}
.socialMenu ul{
    text-align: center;
}
.socialMenu ul li {
    display: inline-block;
    margin-left: -5px;
}
.socialMenu ul li a {
	color: #fff;
	background: #fa4903;
	font-size: 40px;
	margin-left: 5px;
	margin-right: 15px;
	height: 100px;
	width: 100px;
	display: inline-block;
	text-align: center;
	line-height: 100px;
	border-radius: 50%;
} 
.hi{
    /* align-items: center;
    justify-content: center; */
    text-align: center;
    /* margin:auto 45px ; */
    color: #9b59b6;

}
.v{
    padding: 34px;
    border-radius: 34px;
}
.socialMenu ul li a:hover{}
    </style>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.0/css/all.min.css">
    
</head>
<body>
    
    <div class="header-menu">
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About us</a>
               <ul>
                   <li><a href="">whatsapp</a></li>
                   <li><a href="#">instagram</a></li>
                   <li><a href="#">twiter</a></li>
                   <li><a href="https://facebook.com" > facebook</a></li>
                   <li><a href="#">DropDonw item</a></li>
                   <li><a href="#">DropDonw item</a></li>
               </ul> 
            </li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Product</a></li>
            <li><a href="#">Contact us</a></li>
        </ul>
    </div>
   <!-- <div>
    <form action="noaction.in" class="hi">
        <label for="name">name</label>
        <div>
            <input type="text" name="my name" id="name">
        </div>
        <br>
     <div>
      role :<input type="text" name="my role">
    </div>
    <br>
    <div>
        email:<input type="email" name="my email" >
    </div>
    <br>
    <div>
         date: <input type="date" name="my date">
    </div>
    <br>
    <div>
        bonus: <input type="number" name="my bonus">
    </div>
    <br>
    <div>
        are you eligible:<input type="checkbox" name="my eligiblity" >
    </div>
    <br>
    <div>
       gender: male <input type="radio" name="my gender">  female <input type="radio" name="my gender">
       others <input type="radio" name="my gender">
    </div>
    <br>
    <div>
      write about yourself: <br> <textarea name=""  cols="30" rows="10"></textarea>
    </div>
    <div>
        <label for="car">car</label>
        <select name="mycar" id="car">
        <option value="indica">ind</option>
        <option value="swift">swf</option>
    </select>
    </div>

    <br>
    <div>
        <input type="submit" class="v" value="submit now">
        <input type="reset" value="reset now">
    </div>
    </form>
</div> -->
    <div class="socialMenu">
        <ul>
            <li><a href="youtube.com"><i class="fab fa-facebook-f"></i></a></li>
            <li><a href="#"><i class="fab fa-instagram"></i></a></li>
            <li><a href="#"><i class="fab fa-twitter"></i></a></li>
            <li><a href="#"><i class="fab fa-youtube"></i></a></li>
            <li><a href="#"><i class="fab fa-pinterest-p"></i></a></li>
        </ul>
    </div>

</body>
</html>
