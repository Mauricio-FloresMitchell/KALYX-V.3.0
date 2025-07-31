# 💪 KALYX – App Web de Entrenamiento Personalizado (Versión de Prueba)

**KALYX** es una app web *responsive* enfocada en ofrecer una experiencia personalizada de entrenamiento, seguimiento de progreso físico y control de rutinas. Está pensada para usuarios que desean gestionar su entrenamiento de forma práctica, visual y autónoma desde cualquier dispositivo.

---

## 🚧 Estado del Proyecto

> Esta es una **versión de prueba** de KALYX, desarrollada como prototipo funcional. Todos los datos se almacenan únicamente en el navegador local del usuario mediante `localStorage`.  
>  
> **No se requiere registro ni conexión a base de datos externa.**

---

## 🎯 Funcionalidades Principales

### 📅 Plan Semanal
- Visualiza y accede a la rutina del día.
- Consulta el progreso semanal de forma porcentual.
- Accede al total de ejercicios registrados.

### 🏋️ Detalle de Rutinas
- Rutinas organizadas por día de la semana.
- Edición dinámica de ejercicios: nombre, series, repeticiones y video de YouTube.
- Posibilidad de añadir carga (peso) por ejercicio y ver su historial.
- Modal editor intuitivo con campos validados.

### 📈 Carga Evolutiva
- Gráfica de progresión de carga por ejercicio.
- Selección de ejercicio desde lista desplegable.
- Visualización temporal con `Chart.js` y fechas adaptadas.

### ⏱️ Temporizador de Descanso
- Temporizador global para intervalos entre series.
- Controles de pausa y reinicio.
- Visual optimizado para pantallas móviles y escritorio.

### 📊 Progreso Corporal Semanal
- Registro de peso, altura, cuello, cintura y caderas.
- Cálculo automático de **IMC** y **% de grasa corporal** según el método de la Marina de EE. UU.
- Gráficas comparativas de:
  - Peso e IMC
  - Medidas corporales (cuello, cintura, cadera)
- Actualización semanal con registros visuales.

### 📝 Diario de Entrenamiento
- Registro libre de comentarios diarios.
- Edición y eliminación de entradas anteriores.
- Visualización cronológica inversa.

---

## 🌗 Interfaz Visual

- **Modo Oscuro y Claro** (con botón de cambio de tema).
- Diseño responsivo con TailwindCSS.
- Componentes visuales accesibles y estilizados (tarjetas, botones, formularios, íconos).

---

## 🔐 Privacidad y Almacenamiento

- Todos los datos se guardan **únicamente en tu navegador** (no en servidores externos).
- Al borrar caché/localStorage del navegador, los datos también se eliminarán.
- Ideal para uso personal, pruebas, aprendizaje o como base para escalar a backend real.

---

## 🧪 Participa con tu Opinión

Al final de la app encontrarás un botón que te permitirá **responder una encuesta** para evaluar la experiencia y ayudarnos a mejorar:

👉 [Responder Encuesta de Usuario](https://forms.gle/cjM6jbLhSvt95wDr6)

---

## 📲 Acceso a la App

Puedes ver la app funcionando en GitHub Pages aquí:

🔗 [https://tu-usuario.github.io/kalyx-app](https://tu-usuario.github.io/kalyx-app)

---

## ⚙️ Tecnologías Utilizadas

- HTML5
- CSS3 + [TailwindCSS](https://tailwindcss.com/)
- JavaScript Vanilla
- [Chart.js](https://www.chartjs.org/) + adaptador `date-fns`
- `localStorage API` para persistencia de datos offline

---

## 📁 Cómo usar o probar localmente

1. Descarga o clona este repositorio.
2. Asegúrate de que el archivo principal se llame `index.html`.
3. Abre el archivo con un navegador (Chrome recomendado).
4. Todos los datos quedarán guardados en ese navegador y dispositivo.

---

## 📝 Licencia y Uso

Este proyecto puede utilizarse libremente con fines educativos, personales o como base para otros desarrollos. No está autorizado para distribución comercial sin autorización previa.

---

## 💡 ¿Ideas o feedback?

Abrimos el espacio para sugerencias, mejoras o propuestas de colaboración. ¡Gracias por usar **KALYX**!

