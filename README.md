$total = $maths + $science + $english + $computer + $hindi;
$percentage = $total / 5;

if ($percentage >= 80) {
    $grade = "A";
} elseif ($percentage >= 70) {
    $grade = "B";
} elseif ($percentage >= 60) {
    $grade = "C";
} elseif ($percentage >= 50) {
    $grade = "D";
} elseif ($percentage >= 40) {
    $grade = "E";
} else {
    $grade = "F";
}

$result = ($percentage >= 40) ? "Pass" : "Fail";
