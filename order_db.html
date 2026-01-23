<?php
$conn = new mysqli("localhost", "root", "", "restaurant");

$food = strtolower($_POST['food']);

// Check food availability
$check = $conn->query("SELECT * FROM foods WHERE food_name='$food'");

echo "<h1>Order Result</h1>";
if ($check->num_rows > 0) {
    echo "<h3 style='color:green;'>✔ $food is available! Order confirmed.</h3>";
}
 else {
    echo "<h3 style='color:red;'>✖ $food not available.</h3>";

    // Suggest alternative
    $alt = $conn->query("SELECT restaurant FROM alternatives WHERE food_name='$food'");

    if ($alt->num_rows > 0) {
        $row = $alt->fetch_assoc();
        echo "<p>Try here: <b>{$row['restaurant']}</b></p>";
    } else {
        echo "<p>No alternative restaurant found.</p>";
    }
    
}

echo "<br><br><a href='index.php'>Back</a>";
?>
