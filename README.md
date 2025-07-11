<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Search Events</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <div class="container">
    <h1 class="search-title">SEARCH EVENTS</h1>

    <div class="events-grid">
      
      <!-- Repeat this block for each event -->
      <div class="event-card">
        <h3>Event 1</h3>
        <img src="https://static.theprint.in/wp-content/uploads/2024/08/Hockey-1024x576.jpg" alt="Event Image">
        <p>23-May-2020</p>
        <p>Seats Available: 23</p>
        <button class="book-now">Book Now</button>
      </div>

      <div class="event-card">
        <h3>Event 2</h3>
        <img src="https://wallpapers.com/images/featured/tv-series-h49f8zxr4u5zyq40.jpg "alt="Event Image">
        <p>23-May-2020</p>
        <p>Seats Available: 23</p>
        <button class="book-now">Book Now</button>
      </div>

      <div class="event-card sold-out">
        <h3>Event 3 </h3>
        <div class="event-cardsold-out">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT3hC2aN9xQeLuFBdTwkbwdGxiA28Am29z-xg&s" alt="Sold Out event ">
          <p>23-May-2020</p>
          <p>Seats Available: 0</p>
        </div> 
        <button class="sold-out" disabled>Sold Out</button>
      </div>

      <div class="event-card">
        <h3>Event 4</h3>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcStiam3PBRzl8ppZRu9McOZf9lDBwecCsmabQ&s" alt="Event Image">
        <p>23-May-2020</p>
        <p>Seats Available: 23</p>
        <button class="book-now">Book Now</button>
      </div>

      <div class="event-card">
        <h3>Event 5</h3>
        <img src="https://media.newyorker.com/photos/6543f23235570d74bd3ef32e/1:1/w_1706,h_1706,c_limit/Akam-Pelly%20Ruddock%20Mpanzu.jpg" alt="Event Image">
        <p>23-May-2020</p>
        <p>Seats Available: 23</p>
        <button class="book-now">Book Now</button>
      </div>

      <div class="event-card sold-out">
        <h3>Event 6</h3>
        <div class="event-cardsold-out">
          <img src="https://i.pinimg.com/736x/5c/34/fb/5c34fb4d9104f72a6161a63982b0237f.jpg" alt="Sold Out event ">
          <p>23-May-2020</p>
          <p>Seats Available: 0</p>
        </div> 
        <button class="sold-out" disabled>Sold Out</button>
      </div>

      <div class="event-card">
        <h3>Event 7</h3>
        <img src="https://images.pexels.com/photos/158971/pexels-photo-158971.jpeg?cs=srgb&dl=pexels-daniel-43199-158971.jpg&fm=jpg" alt="Event Image">
        <p>23-May-2020</p>
        <p>Seats Available: 23</p>
        <button class="book-now">Book Now</button>
      </div>

      <div class="event-card">
        <h3>Event 8</h3>
        <img src="https://marketplace.canva.com/EAGirgjAY4Y/1/0/1280w/canva-blue-and-green-bold-dynamic-cricket-sports-instagram-post-lXyzR5gfniw.jpg" alt="Event Image">
        <p>23-May-2020</p>
        <p>Seats Available: 23</p>
        <button class="book-now">Book Now</button>
      </div>

    </div>
  </div>

</body>
</html>



CSS CODE 

<link rel="stylesheet" href="style.css">
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 20px;
    background-color: #fafafa;
  }
  
  .container {
    max-width: 1200px;
    margin: auto;
    text-align: center;
  }
  
  .search-title {
    font-size: 28px;
    margin-bottom: 30px;
  }
  
  .events-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
    justify-items: center;
  }
  
  .event-card {
    border: 1px solid #ee9999;
    padding: 15px;
    width: 200px;
    border-radius: 10px;
    background-color: rgb(244, 175, 175);
    box-shadow: 0 2px 6px rgba(0,0,0,0.1);
  }
  
  .event-card h3 {
    margin-top: 0;
  }
  
  .event-card img {
    width: 100px;
    height: 120px;
    border: 2px dashed #f37e7e;
    border-radius: 12px;
    filter: grayscale(40%);
    margin: 10px 0;
  }
  .event-card.sold-out img {
    filter: grayscale(90%) brightness(0.7);

  }
  
  .event-card p {
    margin: 5px 0;
  }
  
  button {
    padding: 6px 12px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
  }
  
  .book-now {
    background-color: #4CAF50;
    color: white;
  }
  
  .sold-out {
    background-color: #ea4b4b;
    color: #0e0e0e;
    cursor: not-allowed;
  }

  

