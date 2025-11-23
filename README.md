# PROTOTIPO: Marketplace de Servicios para Eventos en La Paz
## Proyecto de Grado - UCB

### 1. Descripción del Proyecto
Este prototipo funcional simula la experiencia de usuario del Marketplace propuesto en la tesis. La plataforma conecta a clientes sociales y corporativos con proveedores de eventos verificados (Catering, Música, Fotografía), solucionando la problemática de informalidad y desconfianza en el mercado paceño.

### 2. Tecnologías Utilizadas
El prototipo ha sido desarrollado utilizando tecnologías web estándar, ligeras y modernas, asegurando compatibilidad y facilidad de despliegue:
* **HTML5:** Estructura semántica de las 11 vistas.
* **Tailwind CSS (CDN):** Framework de estilos para un diseño responsivo, limpio y profesional ("Look & Feel" corporativo).
* **JavaScript (Vanilla):** Lógica del lado del cliente para interactividad (filtros, pestañas de login, simulador de carga).
* **FontAwesome:** Iconografía para indicadores visuales de estado y categorías.
* **Google Fonts (Montserrat):** Tipografía seleccionada para mejorar la legibilidad y confianza de la marca.

### 3. Estructura de Archivos
El entregable consta de 11 archivos interconectados que cubren los flujos críticos del usuario:

**Flujo Público (Captación):**
* `index.html`: Landing Page principal con propuesta de valor y categorías.
* `nosotros.html`: Misión, visión, valores y equipo fundador.
* `como-funciona.html`: Explicación del modelo de "Pago en Custodia" y validación.
* `blog.html`: Estrategia de contenidos (Inbound Marketing).
* `articulo-boda.html`: Ejemplo de contenido de valor y liderazgo de opinión.

**Flujo de Búsqueda y Validación:**
* `busqueda.html`: Buscador con filtros por precio, tipo de evento y zona.
* `perfil.html`: Perfil de proveedor (Scarlett Catering) con insignias de verificación (NIT/SEPREC).

**Flujo Transaccional (Seguridad):**
* `login.html`: Ingreso unificado con pestañas para Cliente y Proveedor.
* `cliente-dashboard.html`: Panel de control del usuario (Reservas y Pagos en Custodia).
* `proveedor-dashboard.html`: Panel de gestión del negocio (Finanzas y Solicitudes).
* `mis-eventos.html`: Gestión de estados del evento (Borrador, Confirmado, Finalizado).
* `contrato.html`: Generador automático de contratos legales digitales.

### 4. Instrucciones de Ejecución
1.  Asegúrese de tener todos los archivos `.html` y la carpeta de imágenes (o conexión a internet para las imágenes de stock) en un mismo directorio.
2.  Abra el archivo `index.html` en cualquier navegador web moderno (Chrome, Edge, Firefox).
3.  No se requiere instalación de servidores ni bases de datos (el prototipo corre en el navegador).

### 5. Credenciales de Prueba (Simulación)
Para probar los flujos de usuario logueado, puede usar cualquier credencial genérica o los botones de acceso directo en el Login.
* **Rol Cliente:** Acceso al Dashboard de Camila M.
* **Rol Proveedor:** Acceso al Panel de Scarlett Catering.

---
Desarrollado como parte de la defensa de grado de:
Hanna Fiorella Loayza Carvallo, Camila Moyata Escobar & Emiliano Osuna
Universidad Católica Boliviana "San Pablo" - 2025