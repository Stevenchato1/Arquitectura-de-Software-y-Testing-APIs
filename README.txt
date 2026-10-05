RETO MÓDULO 2 - FITZONE
=======================

EQUIPO
------
Nombre 1: Steven Andrew Huasupoma Olaya


EJERCICIO 1 - API FITZONE
-------------------------
Levantar el servicio desde:

ejercicio1/servicio-fitzone/

Comando:

npx json-server db.json --port 3000

URL base:

http://localhost:3000

La colección de Postman incluye pruebas de:
GET, POST, PUT, PATCH y DELETE.

Data Driven con Newman:

npx newman run .\Reto-FitZone.postman_collection.json --folder 01-DataDriven --iteration-data .\socios-data.csv


EJERCICIO 2 - MOCK SERVER
-------------------------
Mock Server basado en el recurso clases.

Incluye Examples para:
GET, POST (201), PUT, PATCH y DELETE.

El archivo consumo-mock.http consume el Mock mediante:

@mock_url = URL_DEL_MOCK

Ejecutar cada request en VS Code con:

Ctrl + Alt + R


NOTAS
-----
- Mantener la estructura de carpetas solicitada.
- Las capturas contienen las evidencias de ejecución.
- Para el ejercicio 2, reemplazar @mock_url por la URL del Mock Server.