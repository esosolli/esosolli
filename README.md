<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="description" content="Home for professional web design">
	  <meta name="keywords" content="Eso design Home for web design">
  	<meta name="author" content="Brad Traversy">
    <title>Eso Web Design</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
   
       <header>
      <div class="container">
        <div id="Practice">
          <h1>Transform Your Business  </h1>
        </div>
        <h3>Unlock new goal with quality web designs</h3>
          <section id="newsletter">
      <div class="container">
        <h1>Subscribe To Our Newsletter</h1>
        <form>
          <input type="email" placeholder="Enter Email..." required>
          <button type="submit" class="button_1">Subscribe</button>
        </form>
      </div>
    </section>
    </header>   
    
    
    <section id="main">
      <div class="container">
        <article id="main-col">
          <h1 class="page-title">What We Do</h1>
          <ul id="services">
            <li>
              <h3>Website Design</h3>
              <img src="webdesign.png" alt="logo" height="100px">
              <p>We help businesses grow by crafting amazing web experience, writing and maintaining code using various programming languages and frameworks,
creating or implementing website layouts and user interfaces and ensuring the website functions correctly and performs optimally.</p>
						  
            </li>
            <li>
              <h3>Website Maintenance</h3>
              <img src="maintenance.png" alt="logo" height="100px">
              <p>We will ensure your website remains functional, secure, and up-to-date, including tasks like software updates, bug fixes, backups, security monitoring, and performance optimization. </p>
						  
            </li>
            <li>
              <h3>Website Hosting</h3>
              <img src="hosting.png" alt="logo" height="100px">
              <p>We provide technical support, troubleshooting issues, ensuring server uptime and security, and offering customer assistance related to web hosting services and website performance. </p>
						
            </li>
          </ul>
        </article>
        <footer>
   
            <h3>Follow us on </h3>
<a href="https://www.facebook.com/share/1YTsfCT1a5/">FACEBOOK</a>  
        </a>
      <p><h1>Eso Deisgn, Copyright &copy; 2025</p></h1>
    </footer>
  </body>
</html>





body{
  font: 15px/1.5 Arial, Helvetica,sans-serif;
  padding:0;
  margin:0;
  background-color:#f4f4f4;
}

/* Global */
.container{
  width:80%;
  margin:auto;
  overflow:hidden;
}

ul{
  margin:0;
  padding:0;
}

.button_1{
  height:38px;
  background:#e8491d;
  border:0;
  padding-left: 20px;
  padding-right:20px;
  color:#ffffff;
}

.dark{
  padding:15px;
  background:#35424a;
  color:#ffffff;
  margin-top:10px;
  margin-bottom:10px;
}

/* Header **/
header{
  background:#35424a;
  color:#ffffff;
  padding-top:30px;
  min-height:70px;
  border-bottom:#e8491d 3px solid;
}

header #branding{
  float: center;
}

header #branding h1{
  margin:0;
}

header nav{
  float:right;
  margin-top:10px;
}

header .highlight, header .current{
  color:#e8491d;
  font-weight:bold;
}


#showcase h1{
  margin-top:100px;
  font-size:55px;
  margin-bottom:10px;
}

#showcase p{
  font-size:20px;
}



#newsletter h1{
  float:center;
}

#newsletter form {
  float:right;
  margin-top:15px;
}

#newsletter input[type="email"]{
  padding:4px;
  height:25px;
  width:250px;
}

/* Boxes */
#boxes{
  margin-top:20px;
}

#boxes .box{
  float:center;
  text-align: center;
  width:30%;
  padding:10px;
}

#boxes .box img{
  width:90px;
}

/* Sidebar */
aside#sidebar{
  float:right;
  width:30%;
  margin-top:10px;
}

aside#sidebar .quote input, aside#sidebar .quote textarea{
  width:90%;
  padding:5px;
}

/* Main-col */
article#main-col{
  float:left;
  width:65%;
}

footer{
  padding:20px;
  margin-top:20px;
  color: ;
  background-color:#e8491d; 
  text-align: center;
  font-weight:bold;
}

/* Media Queries */
@media(max-width: 768px){
  header #branding,
  header nav,
  header nav li,
  #newsletter h1,
  #newsletter form,
  #boxes .box,
  article#main-col,
  aside#sidebar
  {
    float:none;
    text-align:center;
    width:100%;
  }

  
ul#services li{
  list-style: none;
  padding:20px;
  border: #cccccc solid 1px;
  margin-bottom:5px;
  background:#e6e6e6;
  
