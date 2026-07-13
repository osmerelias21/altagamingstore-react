# Alta Gamers - Tienda de Consolas y Accesorios

Proyecto final desarrollado en React JS para la certificación de Desarrollo Frontend. La aplicación simula una tienda e-commerce de hardware y videojuegos integrada en tiempo real con una base de datos.

## 🚀 Características
* **Navegación Dinámica:** Rutas optimizadas con `react-router-dom` utilizando hooks como `useParams` y `useNavigate`.
* **Persistencia y Estado Global:** Gestión del carrito mediante Context API (`CarritoContext`).
* **Base de Datos en Tiempo Real:** Integración completa con Firebase Firestore para la persistencia de productos y gestión segura de órdenes de compra mediante `writeBatch` para el control de stock.
* **Diseño e Interfaz de Usuario:** Interfaz moderna y responsiva orientada al gaming con componentes globales unificados en el Layout.

## 🛠️ Tecnologías Utilizadas
* React JS
* Vite
* React Router DOM
* Firebase / Firestore
* CSS Modules / Inline Styling

## 🔧 Instalación y Ejecución Local
1. Clonar el repositorio.
2. Ejecutar `npm install` para instalar las dependencias.
3. Crear el archivo de configuración de Firebase en `src/firebase.config.js`.
4. Ejecutar `npm run dev` para iniciar el servidor local.