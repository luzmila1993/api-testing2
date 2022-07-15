# testing-groupname

Repositorio que contiene el pipeline que ejecuta el API-Hook para el testing.

## ap-groupname-testing.yml

Pipeline que ejecuta el API-Hook para el testing.

Se debe actualizar las siguientes variables definidas con el siguiente formato `<variable>`:
| Variable  | Descripción |
| ------------- | ------------- |
| poolname | Nombre del agente.  |

## variables-dev.yml

Archivo que contiene todos los variable groups requeridos en el proceso de testing. Estos deberán crearse por cada ambiente a desplegar.

Los group names definidos son los siguientes:

### apic-testing-dev-001

| Nombre  | Descripción |
| ------------- | ------------- |
| xapikey | Key generado para el consumo del API Hook. |
| xapisecret | Secret generado para el consumo del API Hook. |
