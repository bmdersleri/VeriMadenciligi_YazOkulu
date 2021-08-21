--soap kurulumu
<?php
if(extension_loaded("soap")){
echo "soap kurulu ";
}
else{
echo"soap kurulu değil";
}
?>

<?php

echo php_ini_loaded_file();
?>

--soap veri çekme--

<?php
try{
$istek= new SoapClient('http://localhost/sunucu.php?WSDL');
print_r($istek->kisiler());
}
catch(Exeption $exc){
echo $exc->getMessage();
}
?>