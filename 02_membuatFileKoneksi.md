silakan buat file pada text editor dengan nama <b>koneksi.php</b> 
<pre>
$host = "localhost";
$user = "root";
$pass ="";
$db = "web";
mysql_connect($host,$user,$pass) or die (mysql_error());
mysql_select_db($db) or die (mysql_error());
</pre>
