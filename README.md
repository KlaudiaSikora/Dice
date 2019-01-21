# Dice
<!DOCTYPE html>
<html>
  <body>
    <h3>Roll the dice</h3>
    
    <button onclick="document.getElementById("dice1").innerHTML = 
    getRndInteger(1,6)">Roll a Die</button>
    
    <p id="dice1"></p>
    
    <script>
    function getRndInteger(min, max) {
      return Math.floor(Math.random() * (max - min)) + min;
    }
    </script>
  </body>
</html>
