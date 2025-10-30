<html lang="pl">
<head>
  <meta charset="utf-8" />
  <title>Example: Link to another page</title>
<style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #f4f4f4;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .photo {
            width: 200px;
            background-color: #fff;
            padding: 10px;
            box-shadow: 0 0 5px rgba(0,0,0,0.1);
            text-align: center;
        }
        .photo img {
            max-width: 100%;
            height: auto;
            display: block;
        }
        .description {
            margin-top: 10px;
            font-size: 14px;
            color: #333;
        }
    </style>
</head>
<body>
    <h1>Wielka Trójka</h1>
    <div class="gallery">
        <div class="photo">
            <img src="https://github.com/Chell111/przejsciestron.github.io/blob/main/images/image.jpg?raw=true" alt="Opis zdjęcia 1" />
            <div class="description">Winstonek</div>
        </div>
        <div class="photo">
            <img src="https://github.com/Chell111/przejsciestron.github.io/blob/main/images/Iwan%20w%20pude%C5%82ku.png?raw=true" alt="Opis zdjęcia 2" />
            <div class="description">Ivanek</div>
        </div>
        <!-- Dodaj więcej zdjęć w ten sposób -->
        <div class="photo">
            <img src="https://github.com/Chell111/przejsciestron.github.io/blob/main/images/Maciej.jpg?raw=true" alt="Opis zdjęcia 3" />
            <div class="description">Maciek</div>
        </div>
    </div>

  <!-- Link that opens page2.html in the same tab -->
  <a href="page2.html">Przejdź do natępnej strony :3 (same tab)</a>

  
  </body>

</html>
