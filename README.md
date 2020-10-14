# BigdataProcessing

Usando Spark se realiza:

*	Procesamiento de Streaming descargado desde Kafka.

*	Almacenamiento en Google Cloud de Streaming procesado.

*	Generación de ficheros en formato Parquet almacenados en local.

*	Unificación de ficheros en formato Parquet.

*	Almacenamiento en Google Cloud de información procesada en batch.

Se realiza visualización de la información de las tablas de batch por medio de superset.

##Muestra procesos de almacemiento Google Cloud

*lISTA DE REALACIONES*

 Schema |       Name       | Type  |  Owner
--------+------------------+-------+----------
 public | bytes            | table | postgres
 public | bytes_hourly     | table | postgres
 public | user_metadata    | table | postgres
 public | user_quota_limit | table | postgres

*Tabla Bytes*

      timestamp      |                  id                  | value |        type
---------------------+--------------------------------------+-------+---------------------
 2020-10-13 18:26:00 | luis@gmail.com                       | 15866 | email_bytes_total
 2020-10-13 18:26:00 | gorka@gmail.com                      |  7281 | email_bytes_total
 2020-10-13 18:26:00 | milagros@gmail.com                   |  4927 | email_bytes_total
 2020-10-13 18:26:00 | fede@gmail.com                       |  9652 | email_bytes_total
 2020-10-13 18:28:00 | 44444444-4444-4444-4444-444444444444 | 59663 | antenna_bytes_total
 2020-10-13 18:28:00 | 11111111-1111-1111-1111-111111111111 | 45939 | antenna_bytes_total
 2020-10-13 18:26:00 | 33333333-3333-3333-3333-333333333333 | 66689 | antenna_bytes_total



















































