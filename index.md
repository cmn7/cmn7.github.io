<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title></title>
  <link rel="stylesheet" href="style.css">

  <!-- Papaya.js -->
  <script type="text/javascript" 
          src="https://cdn.jsdelivr.net/gh/rii-mango/Papaya@master/release/current/standard/papaya.js">
  </script>

  <style>
    /* Full viewport for the Papaya container */
    .papaya {
      width: 100%;
      height: 85vh;
      margin: auto;
    }

    body {
      background-color: black;
      color: white;
      font-family: Arial, sans-serif;
      text-align: center;
      margin: 0;
      padding: 0;
    }

    nav, header, main {
      margin-bottom: 20px;
    }
  </style>

  <script>
    var params = {
      "images": ["ShearStiffness_winfo_erode4_new.nii"], // Update with your filename
      "worldSpace": false,
      "showControls": false,
      "showImageButtons": false,
      "showRuler": false,
      "showCrosshairs": false,
      "lut": "Spectrum",        // Use the rainbow color map
      "smoothDisplay": true,
      "orthogonal": false,
      "scrollWheel": true,
      "fullScreen": true,
      "showColorbar": false,    // Hide color bar if present
      /* Additional preferences to hide orientation labels and coords */
      "preferences": {
        "viewer": {
          "showOrientation": false,
          "showCoordinates": false
        }
      }
    };
  </script>
</head>

<body>
  <header>
    <h1></h1>
  </header>

  <nav>
    <a href="index.html">home</a> |
    <a href="about.html">about</a> |
    <a href="research.html">research</a> |
    <a href="contact.html">contact</a>
  </nav>

  <main>
    <p></p>
    <div class="papaya" data-params="params"></div>
  </main>
</body>
</html>
