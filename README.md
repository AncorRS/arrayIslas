<html>
<head>
<title>Islas visitas por mes</title>
</head>
<body>
<center>
<?php

$islasVisitas = array(
    
	
    array('gran canaria' , '100' , '4' , '5','100' , '4' , '5','100' , '4' , '5','100' , '4' , '5'),
    array('tenerife' , '100' , '4' , '5','100' , '4' , '5','100' , '4' , '5','100' , '4' , '5'),
    array('lanzarote' , '100' , '4' , '5','100' , '4' , '5','100' , '4' , '5','100' , '4' , '5'),
    array('hierro' , '100' , '4' , '5','100' , '4' , '5','100' , '4' , '5','100' , '4' , '5'),
	array('la palma' , '100' , '4' , '5','100' , '4' , '5','100' , '4' , '5','100' , '4' , '5'),
	array('gomera' , '100' , '4' , '5','100' , '4' , '5','100' , '4' , '5','100' , '4' , '5'),
    array('fuerteventura' , '100' , '4' , '5','100' , '4' , '5','100' , '4' , '5','100' , '4' , '5')
);



echo '<table border="1">';
echo '<tr><th>visitas</th><th>ene</th><th>feb</th><th>marz</th><th>abril</th><th>mayo</th>
      <th>junio</th><th>julio</th><th>agosto</th><th>sept</th><th>octu</th><th>nov</th><th>dic</th></tr>';
foreach( $islasVisitas as $islas )
{
    echo '<tr>';
    foreach( $islas as $otro )
    {
        echo '<td>'.$otro.'</td>';
    }
    echo '</tr>';
}
echo '</table>';
?>
</center>
</body>
</html>
