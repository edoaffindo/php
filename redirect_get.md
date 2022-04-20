<?php
//Mencoba masuk ke URL tujuan tanpa lewat menu. UNTUK $GET
//! BELOM DI BIKIN DATA NYA
//  SUDAH DIBIKIN DATA NYA
if( 	!isset($_GET["NAMA"]) || 
	!isset($_GET["GAMBAR"]) || 
	!isset($_GET["STATUS"]) || 
	!isset($_GET["ALAMAT"])  ) { //MENGECEK DATA BELOM DIBIKIN // cek apakah tidak ada data di $_GET
//redirect
header("Location : INDEX.PHP")
exit; // agar kodingan di bawah tidak di esekusi
}
?>
