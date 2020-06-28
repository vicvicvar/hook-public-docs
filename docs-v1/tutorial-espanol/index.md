# Tutoriales Optacheck

En los siguientes links encuentra paso a paso guias rapidas del uso de diferentes funcionalidades de Optacheck. 

Un flujo ejemplo entre el usuario y personal es el siguiente:
```mermaid
sequenceDiagram
Encargado ->> Optacheck Web: Organiza y asigna tareas
Optacheck Web ->> Optacheck APP: App obtiene tareas asigandas
Optacheck APP ->> Motorista: Descarga y sincroniza tareas
Motorista ->> Optacheck APP: Completa las tareas asignadas 
Motorista ->> Optacheck APP: Captura notas y visitas
Optacheck APP-->>Optacheck Web: Ubicacion y estado de tareas en tiempo real
Optacheck APP-->>Optacheck Web: Alertas por Geocercas y Paradas no programadas.
Encargado ->> Optacheck Web: Consulta a su motorista 
```

Elige entre las siguientes opciones para entrar al tutorial
> Ingresa a [Web App](/v1/web-app/) Para información del uso de la plataforma web desde un explorador web (Chrome, Firefox, Opera, etc). 

> Ingresa a [App movil](https://stackedit.io/) para información del uso de la aplicación iOS y Android

> Ingresa a [FAQ](https://stackedit.io/) para resolución de dudas y problemas mas comunes 

> Ingresa a [Developer](https://stackedit.io/) mostramos el uso del API e implementacion. 


Si estas guías no resuelven tus dudas, escribenos a soporte@somosopta.com 

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTM3MTkxNDI3MywtMjA3MDM1NDY3MiwxMj
Y0MTU1MDMxXX0=
-->