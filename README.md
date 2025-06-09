# The-Imitation-Assignment-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Image Projects</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f0f0f0;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 2rem;
      padding: 2rem;
    }

    .project {
      border: 2px solid #ccc;
      background: white;
      padding: 1rem;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease;
    }

    .project:hover {
      transform: scale(1.05);
    }

    .project img {
      width: 300px;
      max-width: 100%;
      display: block;
      margin-bottom: 0.5rem;
    }

    .caption {
      font-size: 1rem;
      text-align: center;
      color: #333;
    }
  </style>
</head>
<body>

  <div class="project">
    <img src="images/project1.jpg" alt="Project 1 screenshot" />
    <div class="caption">Project 1</div>
  </div>

  <div class="project">
    <img src="images/project2.jpg" alt="Project 2 screenshot" />
    <div class="caption">Project 2</div>
  </div>

  <div class="project">
    <img src="images/project3.jpg" alt="Project 3 screenshot" />
    <div class="caption">Project 3</div>
  </div>

  <div class="project">
    <img src="images/project4.jpg" alt="Project 4 screenshot" />
    <div class="caption">Project 4</div>
  </div>

  <div class="project">
    <img src="images/football_field.jpg" alt="Football Field Project" />
    <div class="caption">Football Field Project</div>
  </div>

  <div class="project">
    <img src="images/tic-tac-toe.png" alt="Tic-Tac-Toe Overlay" />
    <div class="caption">Tic-Tac-Toe Overlay</div>
  </div>

</body>
</html>
