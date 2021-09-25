# cp-mexico

<img align="right" src="https://pngimage.net/wp-content/uploads/2018/06/mexico-silueta-png-1.png" height="150px">

Recopilacion de datos extraidos del Servicio Postal Mexicano y convertidos a formato `.csv` y `.json` para su posterior implementacion en diferentes proyectos.

# Descripcion de datos

| COLUMNA          | DESCRIPCIÓN                                                           |
|------------------|-----------------------------------------------------------------------|
| d_codigo         | Código Postal asentamiento                                            |
| d_asenta         | Nombre asentamiento                                                   |
| d_tipo_asenta    | Tipo de asentamiento (Catálogo SEPOMEX)                               |
| D_mnpio          | Nombre Municipio (INEGI, Marzo 2013)                                  |
| d_estado         | Nombre  Entidad (INEGI, Marzo 2013)                                   |
| d_ciudad         | Nombre Ciudad (Catálogo SEPOMEX)                                      |
| d_CP             | Código Postal de la Administración Postal que reparte al asentamiento |
| c_estado         | Clave Entidad (INEGI, Marzo 2013)                                     |
| c_oficina        | Código Postal de la Administración Postal que reparte al asentamiento |
| c_CP             | Campo Vacio                                                           |
| c_tipo_asenta    | Clave Tipo de asentamiento (Catálogo SEPOMEX)                         |
| c_mnpio          | Clave Municipio (INEGI, Marzo 2013)                                   |
| id_asenta_cpcons | Identificador único del asentamiento (nivel municipal)                |
| d_zona           | Zona en la que se ubica el asentamiento (Urbano/Rural)                |
| c_cve_ciudad     | Clave Ciudad (Catálogo SEPOMEX                                        |