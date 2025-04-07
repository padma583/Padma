<html lang="en">
  <head>
    <title>Digital Clock</title>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width" />
    <style>
      body{
  background: #000;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

.clock{
  color: #fff;
  font-family: 'Orbitron', sans-serif;
  font-size: 6rem;
  letter-spacing: 1rem;
  font-weight: bold;
}
      </style>
  </head>
  <body>
    <div id="MyClockDisplay" class="clock" onload="showTime()"></div>
    <script>
    function updateTime(){
  let hours = new Date().getHours();
  let minutes = new Date().getMinutes();
  let seconds = new Date().getSeconds(); 
}
      
    </script>
  </body>
</html>
