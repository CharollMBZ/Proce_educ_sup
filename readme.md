## paso 1: redirigete a la carpeta del proyecto

## paso 2: cree el ambiente virtua
python -m venv myenv

## paso 3: activar el entorno virtual
myenv\scripts\activate

### observacion: si esta en macos o linux debe usar:
source myenv/bin/activate

## paso 4: istalar las librerias del archivo requeriments.txt

## paso 5: luego descargar el csv mas reciente de la siguiente url:
https://datosabiertos.mineduc.cl/titulados-en-educacion-superior/

## paso 6: ejecutar la aplicacion
python get_excel_resumen_es.py  