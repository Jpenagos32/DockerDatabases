# Bases de datos para docker con docker compose

- [Corriendo Bases de datos con docker](#corriendo-bases-de-datos-con-docker)
- [Directorio Postgres](#directorio-postgres)

## Corriendo bases de datos con docker

1. Es necesario tener instalado docker desktop y debe estár corriendo

2. Dirigirse hacia la carpeta donde se encuentra el docker compose de la base de datos que necesite

3. En dicha carpeta abrir una terminal

4. Ejecutar el comando docker compose up (opcionalmente se puede agregar la etiqueta -d para que se ejecute en modo detach)

5. Probar la conexión a la base de datos desde la terminar o desde la aplicacion gráfica del RDBMS de nuestra preferencia

6. La base de datos ya se encuentra lista para ser utilizada

## Directorio Postgres

Dentro de este directorio se encuentra el docker compose para la base de datos postgres, cuenta con un volumen para dicha base de datos
