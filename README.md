# Website-V2
Version 2.0 of my own Website. Trying to go for a more professional style and cleaner code this time.

#TODO 
Cookies für Transition

-> Example code für reine website

// Plain File:

<!DOCTYPE html>
<meta charset="utf-8">
<html>
    <head>
        <!--Titel-->
        <title><code.spirit></title>
        <!--Metadata für Embeds etc.-->
        <meta property="og:type" content="website">    
        <meta property="og:title" content="<code.spirit>"> 
        <meta property="og:locale" content="en_US"> 
        <meta property="og:description" content="Hi, I'm Louis, a 15 year old developer."> 
        
        <!--Import von Favicon und CSS-->
        <link rel="shortcut icon" type="image/x-icon" href="assets/img/favicon.png">
        <link rel="stylesheet" type="text/css" href="assets/css/global.css">

        <!--Links für Icons-->
        <script src="https://kit.fontawesome.com/0fb7a47199.js" crossorigin="anonymous"></script>
        <link href="https://fonts.googleapis.com/icon?family=Material+Icons+Outlined" rel="stylesheet">
        <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
    </head>
    <body>
        <main>
            <!--Navbar/Header-->
            <div class="header">
                <ul class="navbar">
                    <!--Left Side-->
                    <li class="navitem"><a href="index.html"><span class="material-icons-outlined" style="vertical-align: -5px;">home</span><span> Home</span></a></li>
                    <li class="navitem"><a href="proj.html"><span class="material-icons-outlined" style="vertical-align: -5px;">code</span> Projects</a></li>
                    <li class="navitem"><a href="skills.html"><span class="material-icons-outlined" style="vertical-align: -5px;">description</span> Skills</a></li>
                    <li class="navitem easteregg"><a href="snake.html"><span class="material-icons-outlined" style="vertical-align: -5px;">tips_and_updates</span> ;)</a></li>
                    <!--Right side-->
                    <li class="navitem dropdown"><a><span class="material-icons-outlined" style="vertical-align: -5px;">more_horiz</span> Other</a>
                        <ul>
                            <li class="navitem current"><a href="games.html">Games</a></li>
                            <li class="navitem"><a href="socials.html">Socials</a></li>
                        </ul>
                    </li>
                    <!--Hobbys, Socials, GitHub-->
                    <li class="navitem"><a><span class="material-icons-outlined" style="vertical-align: -5px;">language</span> Language</a>
                        <ul>
                            <li><a href="/de/index.html">German</a></li>
                        </ul>
                    </li> <!--Dropdown für Sprachen?-->
                </ul>
            </div>
            
            <!--Main Text + Img/GIF-->

            <div class="wrapper">
                <!--Header-->

                <h1 class="name"></h1>

                <!--Main Text-->

                <div class="text-main">

                </div>
            </div>
            <div id="pfp">
                <img src="assets/img/Avatar.png" alt="Whoops! There should be an image.">
            </div>
        </main>
    </body>
</html>