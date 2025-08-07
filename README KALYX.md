KALYX - App de Entrenamiento PRO (Versión Alpha V.A.4.5.)
📝 Descripción del Proyecto
KALYX es una aplicación web de entrenamiento personal en versión Alpha (V.A.4.5.), diseñada para ayudar a los usuarios a gestionar sus rutinas de ejercicio, registrar su progreso y llevar un seguimiento de sus actividades semanales. La aplicación es totalmente local, utilizando localStorage para la persistencia de datos directamente en el navegador del usuario.

✨ Características Principales
Rutinas por Día: Crea, edita y elimina rutinas de ejercicio para cada día de la semana.

Temporizador de Descanso: Un cronómetro integrado con tiempos predefinidos y alertas para gestionar tus descansos.

Seguimiento de Progreso: Visualiza tu progreso con gráficos de peso e índice de grasa corporal, y observa la evolución del peso en cada ejercicio.

Calculadora de Grasa Corporal: Utiliza la fórmula de la Marina de los EE. UU. para estimar el porcentaje de grasa corporal.

Notas Diarias: Agrega comentarios o notas importantes para cada día de entrenamiento.

Tema Personalizable: Alterna entre un tema oscuro y uno claro para una experiencia de usuario adaptada a tus preferencias.

🛠️ Tecnologías Utilizadas
HTML5: Para la estructura y semántica de la página.

Tailwind CSS: Para el estilizado rápido y responsivo de la interfaz.

JavaScript (Vanilla): Para la lógica principal, manejo de eventos y manipulación del DOM.

Chart.js: Para la creación de gráficos dinámicos de progreso.

Phosphor Icons: Conjunto de íconos web para una interfaz visualmente atractiva.

🚀 Instalación y Uso
La aplicación está contenida en un solo archivo index.html, por lo que no se requiere de un servidor web ni de configuraciones complejas.

Descargar el archivo: Obtén el archivo index.html.

Abrir en el navegador: Haz doble clic en el archivo o ábrelo directamente con tu navegador preferido (Chrome, Firefox, Edge, etc.).

La aplicación cargará automáticamente y podrás empezar a usarla de inmediato. Todos tus datos se guardarán localmente en el navegador.

📂 Estructura del Código
El proyecto se compone de un único archivo index.html que integra la estructura, los estilos y la lógica:

<head>: Contiene los metadatos, la carga de las librerías externas (Tailwind, Chart.js, Phosphor Icons) y los estilos CSS personalizados.

<body>: Define la interfaz de usuario con secciones para el encabezado, el selector de días, el contenido principal (rutinas, resumen, comentarios, gráficos) y los modales (añadir ejercicio, actualización).

<script>: Contiene todo el código JavaScript de la aplicación, incluyendo las funciones para la gestión de datos, la renderización de la interfaz, el temporizador y el manejo de eventos.

🧩 Dependencias Externas
La aplicación utiliza las siguientes librerías, cargadas a través de CDN:

Tailwind CSS: <script src="https://cdn.tailwindcss.com"></script>

Chart.js: <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>

Chart.js Date Adapter: <script src="https://cdn.jsdelivr.net/npm/chartjs-adapter-date-fns"></script>

Phosphor Icons: <script src="https://unpkg.com/phosphor-icons"></script>

🤝 Contribuciones
KALYX se encuentra en una fase temprana, por lo que cualquier tipo de contribución es bienvenida. Si deseas colaborar, puedes abrir un issue para reportar errores, sugerir nuevas características o enviar tus cambios mediante un pull request.
