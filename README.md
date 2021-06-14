# php-htmlentities-implode
<?php
//htmlentities()        converts caracters to html entities
//implode()           Return the string from an element of a array
$a="Bangladesh is a <b>beautifull</b><i>country</i>";
echo htmlentities($a);
echo "<br>";
$b= array('bangladesh','is','a','beautiful','country');
print_r (implode( $b));
?>
