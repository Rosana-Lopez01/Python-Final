1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window

2. Creamos una carpeta o directorio: 

mkdir python-final

3. Entramos en ella: 

cd python-final

4. Iniciamos el repositorio:

git init

5. Creamos un archivo:

touch finales.py

6. Abrimos VSC:

code .

7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:

python -V

python3 -V

8. Creamos el entorno virtual en Python:

python3 -m venv venv #Creamos el entorno virtual

9. Activamos el entorno virtual:

source venv/bin/activate #Activamos el entorno virtual en Linux

venv/scripts/activate #En windows

10. Hacemos actualización del pip de Python

python3 -m pip install --upgrade pip #Actualizamos el pip

11. Investigar ¿Qué es el pip y porque lo actualizamos?

12. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.

Qué es el pip y por qué lo actualizamos?
Es la herramienta oficial de Python para instalar y gestionar paquetes (librerías o módulos) desde el repositorio PyPI (Python Package Index).

Actualizar pip es importante porque:

Corrige errores (bugs): como cualquier software, pip puede tener errores que se solucionan en nuevas versiones.

Mejora la seguridad: algunas actualizaciones corrigen vulnerabilidades que podrían afectar tus entornos o proyectos.

Soporte para nuevos estándares: a veces cambia la forma en que se distribuyen los paquetes, y una versión vieja de pip no puede entender los nuevos formatos.

Compatibilidad con nuevas versiones de Python.

Mejor rendimiento: versiones más nuevas suelen instalar paquetes más rápido y con menos errores.


