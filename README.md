<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Heart Shape</title>
  <style>
    .heart {
      position: relative;
      width: 100px;
      height: 100px;
      background-color: red;
      transform: rotate(-45deg);
      margin: 50px auto;
    }

    .heart::before,
    .heart::after {
      content: '';
      position: absolute;
      width: 100px;
      height: 100px;
      background-color: red;
      border-radius: 50%;
      top: 0;
      left: 50%;
      transform: translateX(-50%);
    }

    .heart::after {
      left: 0;
      top: 50%;
      transform: translateY(-50%);
    }
  </style>
</head>
<body>
  <div class="heart"></div>
</body>
</html> 

<!---
ishan25958/ishan25958 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
