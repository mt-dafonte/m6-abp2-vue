# 🧩 M6-ABP7 - Tabla de Personajes Pokémon

## 📘 Aprendizaje Esperado
Utilizar la sintaxis de **templates de Vue** para el despliegue de valores y variables que den solución a un requerimiento.

---

## 🎯 Descripción de la Actividad

En esta actividad se desarrolla una **aplicación web con Vue y Vite**, que muestra una **tabla de personajes ficticios (Pokémon)**.  
El objetivo es aplicar la **sintaxis de plantillas de Vue** y el uso de **directivas (`v-for`, `v-if`, etc.)** para renderizar datos definidos dentro del objeto `data()`.

La tabla despliega el **nombre** y la **descripción** de cada personaje Pokémon, con estilos personalizados y el uso de **Bootstrap** para la tipografía y los estilos base.

---

## 🧱 Requerimientos

- Utilizar **Vue 3** y **Vite** con instalación por **npm**.  
- Los datos deben estar definidos en el objeto `data()` dentro del componente.  
- Usar directivas de Vue (`v-for`) para recorrer el arreglo de personajes.  
- Mostrar los datos (nombre y descripción) en una **tabla HTML**.  
- Aplicar estilos personalizados y usar **Bootstrap** mediante **CDN**.

---

Conceptos Clave Aplicados

Directiva v-for → Permite iterar sobre arreglos y renderizar elementos dinámicamente.

Interpolación {{ variable }} → Inserta valores dentro del HTML.

Componente Vue → Divide la app en partes reutilizables (App.vue y Personajes.vue).

Estilos Bootstrap + CSS personalizado → Mejora la presentación de la tabla.

Data Reactiva (data()) → Almacena los valores que se muestran dinámicamente.

## ⚙️ Instalación del Proyecto

1. **Crear el proyecto con Vite y Vue**
   ```bash
   npm create vite@latest m6_abp7_pokemon -- --template vue
Entrar al directorio del proyecto

bash
Copiar código
cd m6_abp7_pokemon
Instalar dependencias

bash
Copiar código
npm install
Ejecutar el servidor de desarrollo

bash
Copiar código
npm run dev

🗂️ Estructura del Proyecto

m6_abp7_pokemon/
├── index.html
├── package.json
├── vite.config.js
├── /src
│   ├── main.js
│   ├── App.vue
│   ├── /components
│   │   └── Personajes.vue
│   └── /assets
│       └── styles.css
└── /node_modules