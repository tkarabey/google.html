# google.html
<head>
    <title>Google</title>
    <link href="https://fonts.googleapis.com/css?family=Roboto" rel="stylesheet">
	
	<style>
body {
	margin: 0;
	padding: 0;
	font-family: 'Roboto', sans-serif;
}

header {
  width: 100%;
}

ul {
  list-style: none;
}


#nav_bar {
  float: right;
}

#nav_bar li {
  display: inline-block;
  padding: 8px;
}

#nav_bar #giris {
  background: #4887ef; 
  margin-right: 25px;
  padding: 7px 15px;
  border-radius: 3px; 
  font-weight: bold;
}

.nav-links {
  color: #404040;
}

a {
  text-decoration: none;
  color: inherit;
}

li.nav-links a:hover {
  text-decoration: underline;
}

#giris:hover { 
  box-shadow: 1px 1px 5px #999;
}

#giris {
  color: #fff;
}


#google_logo {
  text-align: center;
  display: block;
  margin: 0 auto;
  clear: both;
  padding-top: 112px;
  padding-bottom: 20px;
}

.form {
  text-align: center;
}

#form-search { 
  width: 450px;
  line-height: 32px;
  padding: 20px 10px;
}

.form #form-search {
  padding: 0 8px;
}


.buttons {
  text-align: center;
  padding-top: 30px;
  margin-bottom: 300px;
}


footer  {
  background: #f2f2f2;
  border-top: solid 2px #e4e4e4;
  bottom: 0;
  padding-bottom: 0;
  width: 100%;
  
}

footer ul li {
  display: inline;
  color: #666666;
  font-size: 14px;
  padding: 13px;
}

footer ul {
  float: left;
  padding: 1px;
}

footer ul a:hover {
  text-decoration: underline;
}

.footer-sag {
  float: right;
}

@media screen and (max-width: 400px) {
 
 li.nav-links a {
    display: none;
  }
  
 #google_logo {
   padding: 0;
 }
  
 .buttons {
   display: none;
 }
  
 #form-search {
   width: 80%;

 }
  
 footer {
   bottom: 0;
 }
  
 footer ul {
   float: none;
   padding-bottom: 2px;
    
 }
  
 .footer-sol {
   text-align: center;
   margin: auto; 
   padding-top: 10px;
    
 }
  
 .footer-sag {
   float: none;
   text-align: center;
   
 }
}

@media screen and (max-width: 565px) {
 
  li.nav-links a {
    display: none;
  }
  
  
 #google_logo {
   padding: 0;
 }
  
 .buttons {
   display: none;
 }
  
 #form-search {
   width: 80%;

 }
  
 footer {
   position:absolute;
   bottom:0;
   width:100%;
   height:60px;
 }
  
 footer ul {
   float: none;
   padding-bottom: 2px;
    
 }
  
 .footer-sol {
   text-align: center;
   margin: auto; 
   padding-top: 10px;
    
 }
  
 .footer-sag {
   float: none;
   text-align: center;

 }
}


	</style>
  </head>
  
  <body>
    <header>
      <nav>
        <ul id="nav_bar">
          <li class="nav-links" id="gmail"><a href="#">Gmail</a></li>
          <li class="nav-links"><a href="#">Images</a></li>
          <li id="giris"><a href="#">Sign In</a></li>
        </ul>  
      </nav>  
    </header>  
    
    <div class="google">
      <a href="#" id="google_logo"><img src="https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png" alt=""/></a>
    </div>

    <div class="form">  
      <form>
        <label for="form-search"></label>
        <input type="text" id="form-search" placeholder="Search Google or type URL">
      </form>
    </div>  

    <div class= "buttons">  
      <input type="submit" value="Google Search" id="google_search">
      <input type="submit" value="I'm Feeling Lucky" id="sanslihissediyorum">
    </div>

    <footer>
        <ul class="footer-sol">
          <li><a href="#">Advertising</a></li>
          <li><a href="#">Business</a></li>
          <li><a href="#">About</a></li> 
        </ul>
        <ul class="footer-sag">    
          <li><a href="#">Privacy</a></li>
          <li><a href="#">Terms</a></li>
          <li><a href="#">Settings</a></li>
        </ul>       
    </footer>      
  </body>
