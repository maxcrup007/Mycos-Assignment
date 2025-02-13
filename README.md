Assignment workshop 7 February 2025

- Desktop QR-code
- Mobile QR-code

reference :  [Desktop QR-code](https://www.frontendmentor.io/learning-paths/getting-started-on-frontend-mentor-XJhRWRREZd/steps/67a5d4e3a79a6cf618d2ad77/challenge/submit)



<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="Max" content="Vorawut Phirunpatthanagul">

  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600&display=swap" rel="stylesheet">


  
  <title>Frontend Mentor | QR code component</title>

  <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
  <style>

    @media screen and (max-width: 1440px) {
    body {
        font-size: 16px;
      }
      .container {
        width: 100%;
        padding: 10px;
      }
    }


    body {
            display: flex;
            font-family: 'Outfit', sans-serif; 
            font-weight: 400, 700;
            flex-direction: row;
            align-items: center;
            justify-content: center;
            background:  hsl(212, 45%, 89%);
            height: 100vh;
            box-sizing: content-box;
            width: 1440px;
        }
    
    p   { 
            font-family: 'Outfit', sans-serif; 
            font-weight: bold;
            font-size: 20px; 
            text-align: center; 
            color: hsl(218, 44%, 22%);
            display: flex; 
        }

    .card { 
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background: white;
            padding: 20px;
            border-radius: 18px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            width: 250px;
            max-width: 400px;
            text-align: center;

          }

    .card img { 
            width: 100%;
            height: auto;
            display: block;
            border-radius: 18px;

          }



    .attribution_a { font-family: 'Outfit', sans-serif; font-size: 13px; color: hsl(216, 15%, 48%); text-align: center; }
    .attribution_b { font-family: 'Outfit', sans-serif; font-size: 10px; color: hsl(200, 15%, 48%); text-align: center; }
    
  </style>
</head>
<body>

  <div class="card">

    <img src="images/image-qr-code.png" alt="My Image" width="300">
  
    <p>
      Improve your front-end skills by building projects 
    </p>

 

    <div class="attribution_a">
      Scan the QR code to visit Frontend Mentor and take your coding skills to the next level
    </div>

    <br>

    <div class="attribution_b">
      Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
      Coded by <a href="#">Max Vorawut</a>.
    </div>

    <br>

    </div>
  </div>
  
  
  
</body>
</html>
 
