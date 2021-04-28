!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title> Rock Resume</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
  </head>
  
  *{
  box-sizing: border-box;
}

body {
  margin: 0px;
  padding: 0px;
  font: poppins;
}

#main {
  width: 100%;
  height: 50vh;
  position: relative;
}

nav {
  display: flex;
  justify-content: space-around;
  align-items: center;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background-color: white;
  box-shadow: 5px 10px 30px rgba(0 , 0 , 0 , 0.2)
  z-index :1;
}

.logo img{
  height: 45px;
  width: 95px;
}

.menu{
  list-style: none;
  display : flex;
}

.menu li a{
  height: 40px;
  line-height: 43px;
  margin: 3px;
  padding: 0px 22px;
  display: flex;
  font-size: 1em;
  text-transform: uppercase;
  font-weight: 500;
  letter-spacing: 1px;
  color: gray;
}

a{
  text-decoration: none;
}

.hey{
  color: #39bfbd;
  font-weight: 500;
  font-size: 0.9em;
  border-bottom: 2px solid #39bfbd ;
}

.image{
  width: 400px;
  height: 400px;
}

.image img{
  width: 100%;
  height: 100%;
  object-fit: contain;
}

.content{
  display: flex;
  width: 90%;
  justify-content: space-around;
  align-items: center;
  position: absolute;
  left: 50%;
  right: 50%;
  transform: translate(-50%, -50%)
}

.main-text{
width: 500px;
}

.main-text h1{
  font-size: 3.5em;
  color: #1c3548;
  margin: 0px 0px 10px 0px;
  line-height: 60px;
}

.main-text p{
  color: grey;
}

.resume-btn {
  width: 190px;
  height: 44px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  background-color: #1db096;
  border-radius: 20px;
  box-shadow: 5px 10px 30px rgba(24, 139, 119, 0.2);
}

.resume-btn:hover{
  background-color: #23cdaf;
  transition: all ease 0.2s;
}

.menu li a:hover{
  background-color: #23cdaf;
  color: white;
  box-shadow: 5px 10px 30px rgba(24, 139, 119, 0.2);
  
}
  <body>
    <section id="main">
      <nav>
        <a href="#" class="logo">
          <img src="190919-REBEL-UA-ProjectRock-BTB-Logo-BW.png"alt="The logo of project rock">
        </a>

        <span class="menu-space"></span>

        <ul class="menu">
          <li><a href="#">Home</a></li>
          <li><a href="#">Skillls</a></li>
          <li><a href="#">recent</a></li>
          <li><a href="#">client</a></li>
          <li><a href="#">contacts</a></li>
        </ul>
        <a href="#" class="hey"><strong> Say Hi!</strong></a>
      </nav>
    </section>

    <div class="content">
      <div class="image">
        <img src="rock.png" alt="Rock">
      </div>
      <div class="main-text">
        <h1>Hello, I am the <br> Rock</h1>
        <p>Hey in this video i will be showing you guys how to build a website using only 
          HTML and CSS</p>
          <a href="#" class="resume-btn">See My Resume</a>
      </div>
    </div>

  </body>
</html>
