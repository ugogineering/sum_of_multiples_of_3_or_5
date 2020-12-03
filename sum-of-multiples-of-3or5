<?PHP
// Using (PHP) code to solve problems.
// Multiples of 3 or 5
// With input from @gazsp

// Problem 1
// If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9.
// The sum of these multiples is 23.
// Find the sum of all the multiples of 3 or 5 below 1000.

function sum_of_multiples_of_3_or_5 (int $start_no, int $end_no) {
  // Sum of multiples of 3 or 5 from $start to $end
  $sum = 0;

  if($start_no > $end_no) {
    // In a larger program we'd throw an exception here
    die (print "$end_no must be greater than $start_no");
  }

  // I won't be validating whether $start_no and $end_no are valid integers.
  for ($i = $start_no; $i < $end_no; $i++) {
    if(($i % 3 == 0) || ($i % 5 == 0)){
      $sum += $i;
      // echo "The list of numbers divisible by 3 or 5 from $start - $end are: <br>";
      // print("$i, ");  // This line can be commented out. It doesn't affect the solution.
    }
  }
  // The line below can be commented out if all you want from this function is to return the sum only
  print("<br>The sum of multiples of 3 or 5 from $start_no - $end_no is <b>$sum</b>. Thank you. <br><br>");

  return $sum;
}

echo sum_of_multiples_of_3_or_5(0, 10) . "\n <br>";
echo sum_of_multiples_of_3_or_5(0, 1000) . "\n <br>";
echo sum_of_multiples_of_3_or_5(-10, 50) . "\n <br>";
echo sum_of_multiples_of_3_or_5(0, 1000000) . "\n <br>";
?>
