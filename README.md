Sistema de Monitoreo y Alerta de Salud del Sistema
Este proyecto implementa una herramienta automatizada de monitoreo y alerta de salud del sistema utilizando Grafana, Prometheus y Node Exporter.
Descripción
Esta herramienta proporciona una solución completa para monitorear la salud y el rendimiento de sistemas informáticos. Utiliza Node Exporter para recopilar métricas del sistema, Prometheus para almacenar y consultar estos datos, y Grafana para visualizar la información en dashboards interactivos y configurar alertas.
Componentes

Node Exporter: Recopila métricas del sistema operativo y del hardware.
Prometheus: Sistema de monitoreo y base de datos de series temporales.
Grafana: Plataforma de visualización y alerta.

Características

Monitoreo en tiempo real de métricas del sistema (CPU, memoria, disco, red, etc.)
Dashboards personalizables en Grafana para visualizar métricas clave
Sistema de alertas configurable para notificar sobre problemas potenciales
Almacenamiento eficiente de datos históricos para análisis a largo plazo

Requisitos previos

Sistema operativo Linux (probado en Ubuntu 20.04 LTS)
Acceso root o sudo en el sistema a monitorear

Configuración

Accede a Grafana en http://localhost:3000 (o la dirección IP del servidor).
Inicia sesión con las credenciales por defecto (admin/admin) y cámbialas.
Agrega Prometheus como fuente de datos:

Configuración > Data Sources > Add data source > Prometheus
URL: http://localhost:9090
Guarda y prueba


Importa dashboards predefinidos o crea los tuyos propios.
Configura alertas según tus necesidades.

Uso

Accede a Grafana para ver los dashboards y métricas del sistema.
Configura alertas adicionales según sea necesario.
Utiliza PromQL en Prometheus para consultas avanzadas de métricas.

Contribución
Las contribuciones son bienvenidas. Por favor, abre un issue para discutir cambios mayores antes de crear un pull request.








