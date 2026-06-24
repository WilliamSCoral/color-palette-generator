# 🎨 Generador de Paletas Circular

Herramienta web interactiva para generar, explorar y guardar paletas de colores mediante una rueda SVG animada. Permite copiar colores en formato HEX o HSL, bloquear colores favoritos y guardar paletas para uso futuro.

---

## ✨ Funcionalidades

- Rueda de colores SVG con animación de giro, efecto blur y chispas
- Generación aleatoria de paletas de 6, 8 o 9 colores
- Bloqueo de colores individuales para conservarlos al girar
- Copia de colores en formato HEX o HSL con un clic
- Paletas guardadas con persistencia en `localStorage`
- Diseño responsive: funciona en escritorio y móvil
- Modal de paletas guardadas en móvil

---

## 🗂️ Estructura del proyecto

```
ProyectoM1_WilliamCoral/
├── README.md             # Documentación del proyecto
├── index.html            # Estructura HTML de la aplicación
├── css/
│   └── style.css         # Estilos y diseño responsive
└── js/
    └── script.js         # Lógica, animaciones e interactividad
```

---

## 🌐 Ver en producción

El proyecto está desplegado en **GitHub Pages** y puedes verlo directamente en tu navegador sin instalar nada:

```
https://WilliamSCoral.github.io/ProyectoM1_WilliamCoral/
```

---

## 💻 Ejecutar en local

Tienes dos opciones para correr el proyecto en tu computador.

---

### Opción 1 — Clonar desde GitHub (recomendado)

Necesitas tener **Git** instalado. Puedes verificarlo con:

```bash
git --version
```

Si no lo tienes, descárgalo desde [https://git-scm.com](https://git-scm.com).

**Paso 1 — Clonar el repositorio:**

```bash
git clone https://github.com/WilliamSCoral/ProyectoM1_WilliamCoral.git
```

**Paso 2 — Entrar a la carpeta del proyecto:**

```bash
cd ProyectoM1_WilliamCoral
```

**Paso 3 — Iniciar un servidor local:**

Necesitas un servidor local porque los navegadores modernos bloquean ciertas funciones al abrir archivos HTML directamente.7
La opcion mas viable es:

**Opción 1: Con la extensión Live Server de VS Code:**

1. Instala la extensión **Live Server** en VS Code
2. Haz clic derecho sobre `index.html`
3. Selecciona **"Open with Live Server"**

Se abrirá automáticamente en `http://127.0.0.1:5500`

### Opción 2 — Descargar el ZIP

Si no quieres usar Git:

1. Ve al repositorio en GitHub: `https://github.com/WilliamSCoral/ProyectoM1_WilliamCoral`
2. Haz clic en el botón verde **`<> Code`**
3. Selecciona **"Download ZIP"**
4. Descomprime el archivo descargado
5. Abre la carpeta y sigue el **Paso 3** de la Opción 1 para iniciar el servidor local

---

## 🚀 Desplegar en GitHub Pages

https://WilliamSCoral.github.io/ProyectoM1_WilliamCoral/

---

## 🛠️ Tecnologías utilizadas

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura semántica con BEM |
| CSS3 | Flexbox, variables CSS, media queries |
| JavaScript (ES6+) | Lógica, SVG dinámico, animaciones con `requestAnimationFrame` |
| SVG | Rueda de colores interactiva |
| Canvas API | Partículas de chispas durante el giro |
| localStorage | Persistencia de paletas guardadas |

---

## 📋 Requisitos

- Navegador moderno (Chrome, Firefox, Edge, Safari)
- Node.js (solo si usas `npx serve` para el servidor local)
- Git (solo si clonas el repositorio)

No requiere frameworks, librerías externas ni proceso de compilación.

---
