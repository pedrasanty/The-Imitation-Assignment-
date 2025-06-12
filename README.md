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
    <img src="images_project/butterfly.jpg" alt="Butterfly" />
    <div class="caption">Butterfly</div>
  </div>

  <div class="project">
    <img src="images_project/dinosaur.png" alt="Dinosaur" />
    <div class="caption">Dinosaur</div>
  </div>

  <div class="project">
    <img src="images_project/football_field.jpg" alt="Football Field" />
    <div class="caption">Football Field</div>
  </div>

  <div class="project">
    <img src="images_project/penguins.jpg" alt="Penguins" />
    <div class="caption">Penguins</div>
  </div>

  <div class="project">
    <img src="images_project/seagull.png" alt="Seagull" />
    <div class="caption">Seagull</div>
  </div>

  <div class="project">
    <img src="images_project/theater_stage.jpg" alt="Theater Stage" />
    <div class="caption">Theater Stage</div>
  </div>

  <div class="project">
    <img src="images_project/tic-tac-toe.png" alt="Tic-Tac-Toe" />
    <div class="caption">Tic-Tac-Toe</div>
  </div>

</body>
</html>

