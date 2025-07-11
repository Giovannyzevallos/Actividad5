# 📚 Biblioteca de Componentes UI – Actividad 5

**Autor:** Geovanny Zevallos  
**Proyecto académico – Tecnologías de la Información**

## 📄 Descripción del Proyecto

Este proyecto es una Biblioteca de Componentes UI creada con **HTML**, **CSS** y **Font Awesome**. Simula una interfaz moderna, organizada y reutilizable. Incluye componentes visuales comunes como botones, formularios, tarjetas, modales, acordeones y tooltips.

## 📁 Estructura de Archivos

```
/mi-proyecto
│
├── index.html            # Página principal con todos los componentes
├── stylo.css             # Estilos personalizados para los componentes
├── img.jpg               # Imagen de ejemplo para tarjetas
└── README.md             # Guía básica de uso del proyecto
```

## 🚀 Cómo visualizar el proyecto

1. Abre `index.html` en tu navegador (doble clic o usar Live Server desde VS Code).
2. Asegúrate de tener conexión a internet para cargar los íconos de Font Awesome desde CDN.
3. Visualiza todos los componentes organizados por secciones en una sola página.

---

## 🧩 Componentes incluidos

### 🔘 Botones

- Estilos: Primario, Secundario, Éxito, Advertencia, Peligro, Deshabilitado.
- Tamaños grandes y botones con íconos.

### 🧾 Formularios

- Campos: Texto, Email, Selección de país, Mensaje y Checkbox.
- Estilo responsivo con validación visual.

### 🃏 Tarjetas

- Contienen: Imagen, Título, Descripción y Botón.
- Versión con badge informativo.

### 🔲 Acordeón

- Secciones plegables para agrupar contenido.
- Incluye 3 secciones ilustrativas.

### 🔍 Tooltips

- Mensajes emergentes al pasar el cursor sobre un elemento.

### 🪟 Modal

- Ventana emergente con encabezado, contenido y botones de acción.

---

## 🎨 Personalización

Los colores y estilos están definidos con variables CSS en el selector `:root`. Puedes personalizarlos fácilmente desde `stylo.css`.

```css
:root {
  --primary: #4361ee;
  --success: #28a745;
  --danger:  #dc3545;
  /* Otros colores aquí */
}
```

---

## 📱 Responsive Design

- Adaptado para dispositivos móviles.
- Menú de navegación tipo hamburguesa en pantallas pequeñas.

---

## 💡 Modificar el Navbar

Para ajustar la altura o espaciado del navbar, edita en `stylo.css`:

```css
.navbar {
  padding: 0.6rem 1rem; /* Ajusta el padding vertical */
}
.navbar__link {
  padding: 0.6rem 0.5rem;
  line-height: 2rem;
}
```

---

## 🛠 Tecnologías Utilizadas

- ✅ HTML5  
- ✅ CSS3 con variables personalizadas  
- ✅ Font Awesome  
- ✅ Responsive Design con media queries  


## Autor

Geovanny Zevallos
Actividad 5
Tecnologías de la Información

---

> ¡Explora, modifica y reutiliza estos componentes en tus futuros proyectos web!
