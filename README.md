# netflix_homepage
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            display: flex;
            flex-direction: column;
            
            justify-content: space-around;
            height: 100vh;
            margin: 0;
            background-image: url("netflx_back.png");
         background-size: cover;

        }

        .navigation {
            display: flex;
            flex-direction: row;
            justify-content: space-around;
           
            justify-content: flex-start; 
            margin-bottom: 50px;
            
            color: white; 
        }

        .navigation li {
            margin: 0 80px;
        }

        section {
           
            flex-direction: row;
            justify-content: space-around;
           
            margin-bottom: 600px;
            text-align: center;

       


        }
    </style>
</head>
<body>
    <ul class="navigation">
        
    <section id="home">
        <h2>Home</h2>
        <li><a href="#home">Home</a></li>

        
    </section>

    <section id="Movies">
        <h2>Movies</h2>
        <li><a href="#movies">Movies</a></li>

        
    </section>

    <section id="TV shows">
        <h2>TV shows</h2>
        <li><a href="#project">Tv shows</a></li>


        
    </section>

    <section id="News">
        <h2>News</h2>
        <li><a href="#news">News</a></li>

    </section>

    <section id="Search">
        <h2>Search</h2>
        <li><a href="#search">Search</a></li>
    
        
      
    </ul>

    
    <footer>
        <p>&copy; 2023. All rights reserved.</p>
    </footer>
</body>
</html>
*********************styles**********************
body {
    background-image: url("netflx_back.png");
    background-size: cover;
}

