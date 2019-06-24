# portfolio

<header>
<nav>
  <div id="navbar">
    <a href="#welcome-section">About</a>
    <a href="#projects">My Works</a>
    <a href="#info">Contact me</a>
  </div>
 </nav>
</header>

<div id="welcome-section" class="me">
  <h1>Hi Guys I'm Aravindan</h1>
  <p>I'm a web developer</p>
</div>


<a id="projects" class="works">
  <h2>Some of my Projects are..</h2>
  <a href="https://codepen.io/aravindan33/full/VOOXZr" target="_blank" class="project-link">
  <img class="project-pic"  src="https://cdn.designbump.com/wp-content/uploads/2012/03/coffee-latte-cafe-logos-logo-design-templates-inspiration-001.png" alt="Product Landing Page"></img>
  <div class="project-title">Product Landing Page</div>
</a>
<a href="https://codepen.io/aravindan33/full/QRrbRW" target="_blank" class="project-link">
<img class="project-pic" src="http://realbharat.org/wp-content/uploads/2014/11/a.jpg" alt="Tribute Page"></img>
<div class="project-title">Tribute Page</div>
</a>

<a href="https://codepen.io/aravindan33/full/qGYdVr" target="_blank" class="project-link">
<img class="project-pic" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQyU1Y5QMIB03MGvNQnHeeHURXrSpdICfWhh2grwWPqtQvCIdCm"></img>
<div class="project-title">Survey Form</div>
</a>

<a href="https://codepen.io/aravindan33/full/NVVJPJ" target="_blank" class="project-link">
<img class="project-pic" src="http://icons.iconarchive.com/icons/papirus-team/papirus-mimetypes/256/x-office-document-icon.png"></img>
<div class="project-title">Python Documentation</div>
</a>
</div>

<div id="info"  class="contact">
  <h1>Want to know more about me?</h1>
  <ul>
    <li><a href="https://www.facebook.com/aravindhan.aravi.94">On Facebook</a></li>
    <li><a href="https://github.com/Aravindan07">On Github</a></li>
    <li><a href="https://codepen.io/aravindan33/">On FCC</a></li>
  </ul>
</div>




//CSS Code


body{
  background-image:linear-gradient(#e4d96f,#d5ca60);
}
header{
  text-align:left;
  text-decoration:none;
  font-family:helvetica;
  font-size:15px;
  position:fixed;
  top:0;
  left:0;
  width:100%;
  font-weight:bold;
  display:flex;
}
navbar{
  position:fixed;
  top:0;
  left:0;
  width:100%;
  border-width:320px;
  
}
.me{
  top: 0;
  background: #e0fff9;
  min-height: 50vh;
  padding-top: 30vh;
  text-align:center;
}
.project-pic {
  width: 400px;
  height: 100px;
  border-bottom: 2px solid lightblue;
}
.projects{
  text-decoration: none;
  background-color:white;
  display: inline-block;
  overflow: hidden;
  border: 2px solid lightblue;
  height: 220px;
  width: 280px;
  margin: 40px 100px;
}
.project-title{
  font-weight:bold;
}
a{
  color:green;
}
@media only screen and (max-width: 500px)
{
  .projects{
    margin:40px 0;
  }
  .contact {
  background: #C8F7C5;
  padding-bottom: 160px;
}
}
