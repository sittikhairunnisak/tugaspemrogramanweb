# Tugas_pemrograman_web
# Sitti Khairunnisak (22101053032)
<?php
// Menghitung nilai lambda
function hitungLambda($data) {
    $total = array_sum($data);
    $jumlah_data = count($data);
    
    return $total / $jumlah_data;
}

// Data contoh (misalnya data waktu antara kedatangan pelanggan dalam distribusi Poisson)
$data = [10, 20, 15, 25, 30];

$lambda = hitungLambda($data);

echo "Nilai Lambda adalah: " . $lambda;
?>


