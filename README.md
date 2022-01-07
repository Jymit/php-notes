## readme

```
echo "Hello World";


<?php
echo "This is PHP";
?>

# This is a single-line comment

/* This is a
multi-line
comment */

echo "Hello World";

$txt = "Hello";

$x = 5;
$y = 7;
echo $x + $y;

echo strlen("Hello World!");

echo strrev("Hello World!");

$oldtxt = "Hello World!";
$newtxt = str_replace("World", "Dolly", $oldtxt);

echo 10 * 5;

echo 10 / 2;

var_dump($a == $b);

var_dump($a != $b);

$a = 50;
$b = 10;
if($a > $b) {
  echo "Hello World"; }

$a = 50;
$b = 10;
if ($a != $b) {
  echo "Hello World"; }

$a = 50;
$b = 10;
if
 ($a == $b) {
  echo "Yes";
} 
else
 {
  echo "No";
}

$a = 50;
$b = 10;
if
 ($a == $b) {
  echo "1";
} 
elseif
 ($a > $b) {
  echo "2";
} 
else
 {
  echo "3";
}


switch
 ($color) {  
case
 "red":
    echo "Hello";
    break;
case
 "green":
    echo "Welcome";
    break;
}

switch ($color) {
  case "red":
    echo "Hello";
    break;
  case "green":
    echo "Welcome";
    break;
default:
    echo "Neither";
}


$i = 1; 
while
 ($i < 6) 
{
  echo $i;
  $i++;
}

$i = 1; 
do
 {
    echo $i;
    $i++;
} 
while
 ($i < 6);


for ($i = 0; $i < 10; $i++) {
  echo $i;
}

$colors = array("red", "green", "blue", "yellow"); 
foreach ($colors as $x) { echo $x; }


function myFunction()
 {
  echo "Hello World!";
}

function myFunction() {
  echo "Hello World!";
}
myFunction();

function myFunction($fname, $lname) {
echo $fname; }

function myFunction($fname, $lname) {  
return $lname; }

$fruits = array("Apple", "Banana", "Orange");
echo count($fruits);

$age = array("Peter"=>"35", "Ben"=>"37", "Joe"=>"43");
echo "Ben is " . $age['Ben'] . " years old.";


<form action="welcome.php" method="get">
First name: <input type="text" name="fname">
</form>
<html>
<body>
Welcome <?php echo $_GET["fname"]; ?>
</body>
</html>

> today
echo date("l");
2022.07.01
echo date("Y.m.d");
> time with hour as a 24-hour format
echo date("H:i:s");


<?php include 'footer.php' ;?>

echo readfile("webdict.txt");

$myfile = fopen("webdict.txt", "r");

while(!feof($myfile)) {  echo fgetc ($myfile); }


setcookie("username", "John", time() + (86400 * 30), "/");




```








https://www.w3schools.com/
