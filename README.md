# TarikhTavalod.php
https://quera.org/problemset/615?tab=description
<?php
$a = (string)readline("Enter a brithday: ");
$b = preg_split('//u', $a, null, PREG_SPLIT_NO_EMPTY);
echo "saal:";
for($i = 0; $i < 2; $i++){
	echo $b[$i];
}
echo "\nmaah:";
for($i = 2; $i < 4; $i++){
	echo $b[$i];
}
