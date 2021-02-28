# taytay2332.github.io

<html>
    <head>
      <title>Taylor's Amazing Website</title>
      <style>
    body {
        background: rgb(0, 0, 205);
        color: rgb(45, 45, 45);
        padding: 10px;
        font-family: arial;
    }
    #all-contents {
        max-width: 800px;
        margin: auto;
    }

    /* navigation menu */
    nav {
        background: rgb(255, 20, 147);
        margin: 0 auto;
        margin-bottom: 20px;
        display: flex;
        padding: 10px;
       border-radius: 10px 100px / 120px;
    }
    nav h1 {
        display: flex;
        align-items: center;
        color: white;
        flex: 1;
        margin: 0;
    }
    nav ul {
        list-style-image: none;
    }
    nav li {
        display: inline-block;
        padding: 0 10px;
    }
    nav a {
        text-decoration: none;
        color: #fff;
    }

    /* main container area beneath menu */
    main {
        background: rgb(138, 43, 226);
        display: flex;
       
    }
    .sidebar {
        margin-right: 25px;
        padding: 10px;
    }
    .sidebar img {
        width: 200px;
    }
    .content {
        flex: 1;
        padding: 15px;
    }
    h2, h3 {
        margin: 0px;
    }
</style>
    </head>
    
    <body>
      <div id="all-contents">
          <nav>
            <h1>Taylor's Teriffic Website</h1>
            <ul>
              <li>
                <a href="index.html"> Home </a>
              </li>
              <li>
                <a href="protfolio.html"> Portfolio</a>
              </li>
            </ul>
              
          </nav>
          
          <main>
              <div class="sidebar">
                  <img src="https://scontent-dfw5-1.xx.fbcdn.net/v/t1.0-0/c60.0.206.206a/p206x206/151948387_4389400524408615_1740939673881381189_o.jpg?_nc_cat=111&ccb=3&_nc_sid=da31f3&_nc_ohc=fuW3jhTBj4EAX-QQy2d&_nc_ht=scontent-dfw5-1.xx&tp=27&oh=7a865905b488eb3bd9dd79a770edd032&oe=605F7AEB">
                 
              </div>
              
              <div class="content">
                  
                  <h2>Taylor Forester</h2>
                  <p>Delivery driver at Dominoe's</p>
                  <div id="interests">
                      <h3>Interests</h3>
                      <ul>
                          <li>Coding</li>
                          <li>Art</li>
                          <li>Music</li>
                      </ul>
                      
                  </div>
                  
              </div>
              
          </main>
          
      </div>
      
    </body>
    
</html>



<!DOCTYPE HTML>
<html>
    <head>
      <title>Taylor's Teriffic Website</title>
        <style type="text/css">
            body {
                background: rgb(0, 0, 205);
                color: rgb(45, 45, 45);
                padding: 10px;
                font-family: arial;
            }
            header {
                font-size: 1.5em;
                font-weight: bold;
            }
            h1 {
                margin: 10px;
            }
            #all-contents {
                max-width: 800px;
                margin: auto;
            }
    
            /* navigation menu */
            nav {
                background: rgb(255, 20, 147);
                margin: 0 auto;
                display: flex;
                padding: 10px;
            }
            nav header {
                display: flex;
                align-items: center;
                color: rgb(0, 0, 0);
                flex: 1;
            }
            nav ul {
                list-style-image: none;
            }
            nav li {
                display: inline-block;
                padding: 0 10px;
            }
            nav a {
                text-decoration: none;
                color: #fff;
            }
    
            /* main container area beneath menu */
            main {
                background: rgb(138, 43, 226);
                display: flex;
            }
            .content {
                flex: 1;
                padding: 15px;
            }
               #portfolio {
                list-style-type: none;
                padding-left: 0;
            }
            
            #portfolio li {
                background: #fff;
                padding: 10px;
                border-radius: 10px;
                margin-bottom: 10px;
            }
            
            #portfolio li:hover {
                background: #eee;
            } 
            
            #portfolio a {
                text-decoration: none;
                color: #454545;
            }
        </style>
    </head>

    <body>
      <div id="all-contents">
       <nav>
            <header>Taylor's Teriffic Website</header>
            <ul>
                <li><a href="index.html">Home</a>
                </li>
                <li><a href="portfolio.html">Portfolio</a>
                </li>
            </ul>
        </nav>
          <main>
            <div class="content">
                <h1>Portfolio</h1>
                <ul id="portfolio">
                </ul>
            </div>
        </main>
      </div>
      <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
<script id="portfolioScript">$(document).ready(function() {$.getJSON('projects/projects.json').then(function(data) { data.projects.forEach(function(project){ $('#portfolio').append('<li><a href="projects/' + project.name + '/">' + project.title + ' : ' + project.description + '</a></li>'); }); }); });</script>

    </body>
</html>
