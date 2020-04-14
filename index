<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>PHP Calculator</title>
    <link rel="stylesheet" type="text/css" href="mystyle.css">
  </head>
  <body>
    <!--This is the calculater we see on the website-->
    <form method="get">
      <input type="text" name="num1" placeholder="Number 1">
        <br>
      <select name="operator">
        <option>Select option</option>
        <option>Add</option>
        <option>Subtract</option>
        <option>Multiply</option>
        <option>Divide</option>
      </select>
        <br>
      <input type="text" name="num2" placeholder="Number 2">
      <br>
      <button type="submit" name="submit">Calculate</button>
    </form>
    <p>The answer is:</p>
    <?php
      if (isset($_GET['submit'])) {
        $result1 = $_GET['num1'];
        $result2 = $_GET['num2'];
        $operator = $_GET['operator'];
        switch ($operator) {
          case "Select option":
            echo "You need to select an operator!";
            break;
          case "Add":
            echo $result1 + $result2;
            break;
          case "Subtract":
            echo $result1 - $result2;
            break;
          case "Multiply":
            echo $result1 * $result2;
            break;
          case "Divide":
            echo $result1 / $result2;
            break;
          default:
            echo "Error!";
            break;
        }
      }
    ?>
  </body>
</html>
