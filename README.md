<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Quadrant Layout</title>
  <style>
    /* Main container for all quadrants */
    .container {
      display: grid;
      grid-template-columns: 50% 50%; /* 2 columns, each 50% width */
      grid-template-rows: 25% 50% 25%; /* 3 rows, with respective height percentages */
      height: 100vh; /* Full viewport height */
      width: 100%;
      border: 1px solid #000;
    }

    /* Top Left Quadrant (Most Used Languages + Bug Catcher) */
    .top-left {
      grid-column: 1 / 2; /* 1st column */
      grid-row: 1 / 2;    /* 1st row */
      border-right: 1px solid #000;
      border-bottom: 1px solid #000;
    }

    /* Right Quadrant (Tools & Technologies) */
    .right {
      grid-column: 2 / 3; /* 2nd column */
      grid-row: 1 / 3;    /* From 1st to 3rd row (spans 2 rows) */
      border-left: 1px solid #000;
      border-bottom: 1px solid #000;
    }

    /* Middle Left Quadrant (Research Interest) */
    .middle-left {
      grid-column: 1 / 2; /* 1st column */
      grid-row: 2 / 3;    /* 2nd row */
      border-top: 1px solid #000;
      border-right: 1px solid #000;
    }

    /* Bottom Section (Pixel Art Wallpaper) */
    .bottom-section {
      grid-column: 1 / 3; /* Spans across both columns */
      grid-row: 3 / 4;    /* 3rd row */
      border-top: 1px solid #000;
    }

    /* For demonstration, giving the quadrants background colors */
    .top-left {
      background-color: #f0f0f0;
    }

    .right {
      background-color: #e0e0e0;
    }

    .middle-left {
      background-color: #d0d0d0;
    }

    .bottom-section {
      background-color: #c0c0c0;
    }
  </style>
</head>
<body>

  <div class="container">
    <!-- Top Left Quadrant -->
    <div class="top-left">
      <!-- Content for Top Left (Most Used Languages + Bug Catcher) -->
      <p>Top Left</p>
    </div>
    
    <!-- Right Quadrant -->
    <div class="right">
      <!-- Content for Right (Tools & Technologies) -->
      <p>Right</p>
    </div>

    <!-- Middle Left Quadrant -->
    <div class="middle-left">
      <!-- Content for Middle Left (Research Interest) -->
      <p>Middle Left</p>
    </div>

    <!-- Bottom Section -->
    <div class="bottom-section">
      <!-- Content for Bottom Section (Pixel Art Wallpaper) -->
      <p>Bottom Section</p>
    </div>
  </div>

</body>
</html>


<!-- 
----
[<img src="https://github-profile-trophy.vercel.app/?username=durgeshsamariya&row=2&column=3" />](https://github.com/ryo-ma/github-profile-trophy)
[<img src="https://github-readme-stats.vercel.app/api?username=durgeshsamariya&theme=algolia&count_private=true&include_all_commits=true&show_icons=true" />](https://github.com/anuraghazra/github-readme-stats)
[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=durgeshsamariya&theme=dark)](https://github.com/DenverCoder1/github-readme-streak-stats)
[![Durgesh's Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=themlphdstudent&theme=algolia&hide=Jupyter&layout=compact&show_icons=true)](https://github.com/anuraghazra/github-readme-stats)
 -->
