<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>jo<3sk</title>
  <style>
    body {
      font-family: 'Arial, sans-serif';
      background-color: #ffe6e6;
      color: #333;
      text-align: center;
      padding: 50px;
    }
    h1 {
      font-size: 3rem;
      color: #ff5e78;
    }
    .countdown {
      font-size: 2rem;
      margin-top: 20px;
    }
    .heart {
      font-size: 5rem;
      color: #ff5e78;
      margin: 20px 0;
    }
  </style>
</head>
<body>
  <h1>jo<3sk</h1>
  <div class="heart">❤️</div>
  <p class="countdown">Calculating time to home...</p>

  <script>
    const countdownElement = document.querySelector('.countdown');
    const targetDate = new Date('2024-01-20T00:00:00');

    function updateCountdown() {
      const now = new Date();
      const diff = targetDate - now;

      if (diff > 0) {
        const days = Math.floor(diff / (1000 * 60 * 60 * 24));
        const hours = Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
        const minutes = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
        const seconds = Math.floor((diff % (1000 * 60)) / 1000);

        countdownElement.textContent = `${days} days, ${hours} hours, ${minutes} minutes, ${seconds} seconds to home ❤️`;
      } else {
        countdownElement.textContent = "Welcome Home! ❤️";
      }
    }

    setInterval(updateCountdown, 1000);
  </script>
</body>
</html>
