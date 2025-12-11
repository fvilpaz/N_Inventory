# 📦 N_Inventory

Sistema de gestión de inventario ligero basado en una única página web (HTML/JavaScript) con persistencia local y funcionalidad de Modo Día/Noche.

## ⚡ Funcionalidades principales

* **Persistencia de datos:** Los datos se guardan automáticamente en el almacenamiento local del navegador (`localStorage`).
* **Operaciones CRUD:** Añadir, eliminar, sumar y restar cantidades de artículos.
* **Reinicio Global:** Botón para poner todas las cantidades del inventario a cero para la planificación del siguiente periodo.
* **Búsqueda Rápida:** Filtro por nombre de artículo o tipo.
* **Temas Visuales:** Toggle para cambiar entre Modo Oscuro (por defecto) y Modo Claro (Sol/Luna ☀️/🌙).
* **Ordenación:** Ordenación de tablas por Artículo, Tipo o Cantidad.

## 🛠️ Tecnologías

* **HTML5 / CSS3** – Estructura y estilo (Dark Mode y Light Mode).
* **JavaScript ES6+** – Lógica, manipulación del DOM, y gestión de `localStorage`.

## 🚀 Cómo usar

Para empezar a usar N_Inventory:

1.  **Clona el repositorio:**
    ```bash
    git clone [https://github.com/tu-usuario/N_Inventory](https://github.com/tu-usuario/N_Inventory)
    ```
2.  **Navega a la carpeta:**
    ```bash
    cd N_Inventory
    ```
3.  Abre el archivo **`index.html`** directamente en tu navegador.

## 📝 Nota

Este proyecto es una herramienta simple y local. La persistencia de datos depende del navegador y no está diseñada para ser compartida o utilizada en entornos de producción sin un backend dedicado (como Java/JPA).

## 📌 Objetivo

Ofrecer una solución simple y rápida para el control de stock, accesible sin necesidad de servidores ni instalaciones complejas.