# CODSOFT-Level-1-
//It is a landing page of Netflix which has been cfreated using HTML on VSCODE
<html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Netflix</title>
  <style>
    body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
  }
  
  .container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
  }
  
  header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #111;
    padding: 10px 0;
  }
  
  .logo {
    width: 200px;
    height: 100px;
  }
  
  nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
  }
  
  nav li {
    display: inline;
    margin-left: 20px;
  }
  
  nav a {
    color: #fff;
    text-decoration: none;
  }
  
  nav a:hover {
    text-decoration: underline;
  }
  
  main {
    background-color: #222;
    padding: 20px;
  }
  
  .content-section {
    margin-bottom: 40px;
  }
  
  .content-section h2 {
    color: #fff;
  }
  
  .card-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
  }
  
  .card {
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
    transition: transform 0.2s;
  }
  
  .card img {
    width: 80%;
    height: 630px;
    object-fit: fill;
  }
  
  .card h3 {
    color: #fff;
    padding: 10px;
    font-size: 18px;
  }
  
  footer {
    background-color: #111;
    color: #fff;
    text-align: center;
    padding: 10px;
  }
  
  </style>
</head>

<body>
  <header>
    <div class="container">
      <img src="https://www.edigitalagency.com.au/wp-content/uploads/Netflix-logo-red-black-png.png" alt="Netflix Logo" class="logo">
      <nav>
        <ul>
          <li><a href="#" target="_blank">Home &nbsp;&nbsp;|</a></li>
          <li><a href="#" target="_blank">TV Shows &nbsp;&nbsp;|</a></li>
          <li><a href="#" target="_blank">Movies</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main>
    <section class="content-section">
      <h2>Trending Now</h2>
      <div class="card-container">
        <div class="card">
          <img src="https://pbs.twimg.com/media/FvUVt3hXgAAxP1H.jpg" alt="Movie 1">
          <h3>Oppenheimer</h3>
        </div>
        <div class="card">
          <img src="https://mymodernmet.com/wp/wp-content/uploads/2023/04/barbie-movie-posters-4.jpg" alt="Movie 2">
          <h3>Barbie</h3>
        </div>
        <div class="card">
            <img src="https://s3.amazonaws.com/static.rogerebert.com/uploads/movie/movie_poster/mission-impossible---dead-reckoning-part-one-2023/large_mission-impossible-dead-reckoning-part-one-MIDRP1_Dom_2037x3000_Payoff_Digital_1sht_01_Fin18_rgb.jpg" alt="Movie 3">
            <h3>Mission Impossible :Dead Reckoning</h3>
          </div>
      </div>
    </section>

    <section class="content-section">
      <h2>Most Played TV Shows</h2>
      <div class="card-container">
        <div class="card">
          <img src="https://wallpapercave.com/wp/wp9354260.jpg" alt="TV Show 1">
          <h3>Lucifer</h3>
        </div>
        <div class="card">
          <img src="https://m.media-amazon.com/images/M/MV5BMDZkYmVhNjMtNWU4MC00MDQxLWE3MjYtZGMzZWI1ZjhlOWJmXkEyXkFqcGdeQXVyMTkxNjUyNQ@@._V1_FMjpg_UX1000_.jpg" alt="TV Show 2">
          <h3>Stranger Things</h3>
        </div>
        <div class="card">
            <img src="https://mypostercollection.com/wp-content/uploads/2018/08/Game-Of-Thrones-Poster-MyPosterCollection.com-38.jpg" alt="TV Show 3">
            <h3>Game Of Thrones</h3>
          </div>
      </div>
    </section>
    <section class="content-section">
      <h2>Latest</h2>
      <div class="card-container">
        <div class="card">
          <img src="https://m.media-amazon.com/images/I/71ZaeJnJpjL.jpg" alt="Movie 4">
          <h3>Gran Turismo</h3>
        </div>
        <div class="card">
          <img src="https://m.media-amazon.com/images/I/617KVvHRJSL.jpg" alt="Movie 5">
          <h3>The Flash</h3>
        </div>
        <div class="card">
            <img src="https://images-na.ssl-images-amazon.com/images/I/61Di5-W8XgL.jpg" alt="Movie 6">
            <h3>Fast X</h3>
         </div>
      </div>
    </section>
  </main>

  <footer>
    <p>&copy; 2023 My Netflix Clone</p>
  </footer>
</body>

</html>
