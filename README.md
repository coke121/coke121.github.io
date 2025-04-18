<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Gorilla Tag Archive</title>
  <style>
    body {
      background-color: #1e1e1e;
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: flex-start;
      min-height: 100vh;
      font-family: Arial, sans-serif;
    }

    .gradient-text {
      background: linear-gradient(to right, purple, pink);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      text-align: center;
      margin-top: 60px;
    }

    h1.gradient-text {
      font-size: 2.5rem;
    }

    h2.gradient-text {
      font-size: 1.5rem;
      margin-top: 20px;
    }
  </style>

  <script>
    // This script will remove any unwanted "coke121" text if it's appearing dynamically
    window.onload = function() {
      // Remove unwanted elements (check for a div or any content that shouldn't be there)
      const unwantedText = document.querySelectorAll('div, span, p');
      unwantedText.forEach(element => {
        if (element.textContent.includes('coke121')) {
          element.remove();  // Remove the element containing the unwanted text
        }
      });
    };
  </script>
</head>
<body>
  <h1 class="gradient-text">GORILLA TAG ARCHIVE CURRENT VERSION</h1>
  <h2 class="gradient-text">CRITTER UPDATE 2025</h2>
</body>
</html>
