<?php 
// Function to sort an array of strings by their length
function sortByLength($arr){ 
    usort($arr, function($a, $b) {
        return strlen($a) - strlen($b);
    }); 
  
    return $arr; 
} 
  
// Example 
$arr = array("Cat", "Dog", "Elephant"); 
  
// Sort the array 
$result = sortByLength($arr); 
  
// Print the result 
print_r($result); 
?> 
