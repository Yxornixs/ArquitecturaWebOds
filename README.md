# ArquitecturaWeb - Modulo 1 (1,2)
# ArquitecturaWebOds
Objetivos de Desarrollo Sustentable.


# Nombre Del grupo: RHN
# Integrantes: Roxana Albanesi
# Descripción del negocio elegido: ODS - Objetivo de desarrollo Sostenible 
Los Objetivos de Desarrollo Sostenible (ODS), también conocidos como Objetivos Mundiales, son un llamado universal a la adopción de medidas para poner fin a la pobreza, proteger el planeta y garantizar que todas las personas gocen de paz y prosperidad. ... Los ODS son una agenda inclusiva.

Generar CRUD: OBJETIVOS,METAS/INDICE, LEYES O PROYECTOS DE LEY ASOCIADOS A LOS OBJETIVOS.
Consulta: Seleccion de Objetivos, visualizacion de metas, leyes o proyectos que aporten al cumplimiento de las mismas.



POST   \ODS        – 201 CREADA - CREA UN NUEVO OBJETIVO.

POST   \ODS\METAS        – 201 CREADA - CREA UN NUEVO OBJETIVO Y SUS METAS.

POST   \ODS\METAS\LEY       – 201 CREADA - CREA UN NUEVO OBJETIVO Y SUS METAS Y LEY.

PUT  \ODS(NUMERO) - 200OK - ACTUALIZA UNA ODS.

PUT  \ODS\METAS(NUMERO) - 200OK - ACTUALIZA UNA ODS METAS.

PUT  \ODS\METAS\LEY(NUMERO) - 200OK - ACTUALIZA UNA ODS METAS Y LEY.

GET   \ODS        - 200OK - RECUPERA TODAS LOS OBJETIVOS CARGADOS.

GET   \ODS\(NUMERO) – 200OK - RECUPERA EL OBJETIVO SELECCIONADO.

DELETE \ODS\(NUMERO)- 205 Reset Content - BORRA EL OBJETIVO.
