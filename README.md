# Support-Centre-v2.9.0-Advanced-PHP-Ticket-System
Support Centre v2.9.0 - Advanced PHP Ticket System Spanish languages


Editar el siguiente archivo: config.php

./application/config/config.php

Cambiar la siguiente línea:

$config['language']	= 'english';
		
a la siguiente línea:

$config['language']	= 'español';


--------------
Da error?

Modificar el archivo index.php en ROOT directory 
Agregar el siguiente código al principio:
ob_start();


ejemplo:
<?php
// Descomentar la siguiente línea por si da problemas con
//ini_set(): Headers already sent. You cannot change the session module's ini settings at this time in codeigniter
//
// ob_start(); 
//
