# DIGESETT

🚓 FINAL: Aplicación Web para la DIGESETT
Descripción
Este proyecto consiste en el desarrollo de una aplicación web para la Dirección General de Seguridad de Tránsito y Transporte Terrestre (DIGESETT), con el fin de gestionar las multas de tránsito. La aplicación se divide en tres módulos principales: Agente, Oficina Central y Administrativo, con funcionalidades que permiten a los agentes registrar y gestionar multas, y a la oficina central administrar la base de datos de multas y agentes.

Tecnologías Utilizadas
Backend: SQLite
Frontend: HTML, CSS, JavaScript (opcionalmente frameworks como React, Vue, etc.)
Autenticación: Login con cédula y clave
Mapas: Implementación con coordenadas para visualizar las multas
Módulos
1. Módulo de Agente 👮‍♂️
Los agentes pueden iniciar sesión con su cédula y clave y realizar las siguientes funciones:

Registrar Multa 📝: Captura de datos como cédula, nombre, concepto, descripción, coordenadas y foto.
Listado de Multas 📋: Ver el listado de multas registradas por el agente, incluyendo fecha y estado.
Mapa con Mis Multas 🗺️: Visualización de un mapa con las multas registradas en las últimas 4 semanas.
Comisión por Mes 💰: Cálculo y visualización de la comisión mensual del agente (10% por cada multa).
Acerca de 👤: Información sobre los programadores, incluyendo foto y enlace a Telegram.
Salir 🚪: Cerrar sesión.
2. Módulo de Oficina Central 🏢
El personal de la oficina central puede gestionar las multas y agentes con las siguientes opciones:

Gestionar Multas 🔍: Buscar y actualizar multas (cobradas o perdonadas).
Reporte de Ingresos 📈: Ver el total de ingresos por multas en un mes y agruparlas por tipo.
Mapa de Multas 🗺️: Visualización de todas las multas registradas en un periodo específico.
Gestionar Agentes 👥: Agregar, editar y desactivar agentes.
3. Módulo Administrativo ⚙️
Este módulo permite a los administradores gestionar usuarios y conceptos de multas:

Gestionar Conceptos de Multas 📝: Crear, editar y eliminar conceptos de multas.
Gestión de Usuarios 👤: Gestión de los usuarios de la oficina central.
Credenciales de Administrador
Usuario: adamix
