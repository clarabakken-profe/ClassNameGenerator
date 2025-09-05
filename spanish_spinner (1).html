<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <title>2-Wheel Spinner: Animales y Colores</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      background: #f4f4f9;
    }
    h1 {
      margin-bottom: 20px;
    }
    .spinner-container {
      display: flex;
      gap: 40px;
      margin-bottom: 30px;
    }
    .wheel {
      width: 200px;
      height: 200px;
      border-radius: 50%;
      border: 5px solid #333;
      position: relative;
      overflow: hidden;
    }
    .wheel div {
      position: absolute;
      width: 50%;
      height: 50%;
      top: 50%;
      left: 50%;
      transform-origin: 0% 0%;
      text-align: right;
      padding-right: 5px;
      font-size: 14px;
      font-weight: bold;
    }
    button {
      padding: 10px 20px;
      font-size: 16px;
      margin: 5px;
      cursor: pointer;
    }
    #result {
      margin-top: 20px;
      font-size: 22px;
      font-weight: bold;
      color: #222;
    }
  </style>
</head>
<body>
  <h1>🎡 Spinner de Animales y Colores</h1>
  <div class="spinner-container">
    <div class="wheel" id="wheelAnimals"></div>
    <div class="wheel" id="wheelColors"></div>
  </div>
  <div>
    <button onclick="spinWheels()">🎯 ¡Girar!</button>
  </div>
  <div id="result"></div>

  <script>
    // Animals with gender
    const animals = [
      { word: "León", gender: "m" },
      { word: "Tigre", gender: "m" },
      { word: "Oso", gender: "m" },
      { word: "Lobo", gender: "m" },
      { word: "Zorro", gender: "m" },
      { word: "Gato", gender: "m" },
      { word: "Perro", gender: "m" },
      { word: "Conejo", gender: "m" },
      { word: "Tortuga", gender: "f" },
      { word: "Delfín", gender: "m" },
      { word: "Águila", gender: "f" },
      { word: "Caballo", gender: "m" }
    ];

    const colors = [
      "Rojo","Azul","Verde","Amarillo","Morado",
      "Anaranjado","Negro","Blanco","Rosado","Gris",
      "Marrón","Dorado"
    ];

    function createWheel(id, items) {
      const wheel = document.getElementById(id);
      const slice = 360 / items.length;
      items.forEach((item, i) => {
        const div = document.createElement("div");
        div.style.transform = `rotate(${i * slice}deg) translate(-100%, -100%)`;
        div.innerText = item.word || item;
        wheel.appendChild(div);
      });
    }

    createWheel("wheelAnimals", animals);
    createWheel("wheelColors", colors);

    function pluralize(word) {
      if (word.endsWith("z")) {
        return word.slice(0, -1) + "ces";
      } else if (word.endsWith("s")) {
        return word;
      } else if (/[aeiouáéíóú]$/.test(word)) {
        return word + "s";
      } else {
        return word + "es";
      }
    }

    function spinWheels() {
      const animalObj = animals[Math.floor(Math.random() * animals.length)];
      const color = colors[Math.floor(Math.random() * colors.length)];

      const pluralAnimal = pluralize(animalObj.word);
      const pluralColor = pluralize(color);

      const article = animalObj.gender === "f" ? "Las" : "Los";

      document.getElementById("result").innerText = `Tu equipo es: ${article} ${pluralAnimal} ${pluralColor}!`;
    }
  </script>
</body>
</html>
