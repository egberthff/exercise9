<!DOCTYPE html>
<html>
<head>
  <title>Box Model Sample</title>
  <style>
    .box {
      width: 250px;
      height: 250px;
      border: 2px solid black;
      padding: 20px;
      margin: 30px;
      background-color: white;
      text-align: center;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }
    
    .box img {
      border-radius: 50%;
      max-width: 95%;
      max-height: 80%;
      border-widtd:12px;
 }
  </style>
</head>
<body>
  <div class="box">
    <img src="https://images.pexels.com/photos/14440674/pexels-photo-14440674.jpeg" alt="Sample Image">
    <p style="text-align: center;">I am a Cat!</p>
  </div>
</body>
</html>
