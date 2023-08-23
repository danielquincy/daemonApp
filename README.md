# daemonApp
Una aplicación que este leyendo una carpeta cada minuto y que cuando se detecte un archivo nuevo este mismo sea cargado a una sola tabla llamada "call_detail_records" en una base de datos llamada "ussd", en base de datos MSSQL. 

De igual forma se necesita almacenar una tabla de control "cdr_logs" que registre el nombre del archivo, 
la fecha y hora del inicio de la carga, la hora de fin, número de registros cargados, número de registros fallidos.
