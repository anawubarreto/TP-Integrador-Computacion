
TP Integrador - Computación

Este repositorio contiene la entrega final del Trabajo Práctico Integrador, estructurado según los requerimientos solicitados para el respaldo de los directorios del sistema.

 Contenido del Repositorio
Los siguientes directorios fueron empaquetados de forma individual utilizando la herramienta `tar`:
root.tar.gz: Respaldo del directorio `/root`
etc.tar.gz: Respaldo del directorio `/etc`
opt.tar.gz: Respaldo del directorio `/opt`
www_dir.tar.gz: Respaldo del directorio `/www_dir`
backup_dir.tar.gz: Respaldo del directorio `/backup_dir`

 Fraccionamiento de /var
Debido al tamaño considerable del directorio `/var`, y para cumplir de forma óptima con la subida a la plataforma, se utilizó la herramienta `split` integrada con `tar` para segmentar el archivo comprimido en partes más pequeñas de 10MB:
var_part_aa hasta var_part_ag

