# MÓDULO 6: Desarrollo de Interfaces Interactivas con Framework VUE
María Teresa de la Fuente C.

## Ruta de repositorio: 
mt-dafonte/m6-abp2-vue

# Actividad M6-ABP2_Templates y rendering en VUE

---

## Descripción

Desarrollo de **aplicación web con Vue y Vite**, que muestra una **tabla de personajes ficticios (Pokémon)**.  
El objetivo es aplicar la **sintaxis de plantillas de Vue** y el uso de **directivas (`v-for`, `v-if`, etc.)** para renderizar datos definidos dentro del objeto `data()`.

La tabla despliega el **nombre** y la **descripción** de cada personaje Pokémon, con estilos personalizados y el uso de **Bootstrap** para la tipografía y los estilos base.

---

## Conceptos Clave Aplicados

Directiva v-for → Permite iterar sobre arreglos y renderizar elementos dinámicamente.

Interpolación {{ variable }} → Inserta valores dentro del HTML.

Componente Vue → Divide la app en partes reutilizables (App.vue y Personajes.vue).

Estilos Bootstrap + CSS personalizado → Mejora la presentación de la tabla.

Data Reactiva (data()) → Almacena los valores que se muestran dinámicamente.

## Instalación del Proyecto

1. **Entrar al directorio del proyecto**
  
```
cd m6_abp7_pokemon
```
2. **Instalar dependencias**

```
npm install
```

3. **Ejecutar el servidor de desarrollo**

```
npm run dev
```

## Estructura del Proyecto
```
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
```