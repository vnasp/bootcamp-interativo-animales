# Avistamiento de Animales

Proyecto desarrollado como desafío del **Bootcamp Frontend Developer de Talento Digital para Chile**. Bitácora interactiva para registrar avistamientos de fauna chilena. Permite seleccionar especies, agregar comentarios, previsualizar el animal y escuchar su sonido.

> **Nota:** Este es un proyecto académico interactivo, no una aplicación de registro real.

## Vista previa

[Ver en GitHub Pages](https://vnasp.github.io/bootcamp-interativo-animales/)

## Funcionalidades

- Registro de avistamientos con formulario (especie, edad, comentarios)
- Previsualización en vivo del animal seleccionado
- Galería de tarjetas con los registros
- Reproducción de sonidos por especie
- Modal con detalle del avistamiento
- Eliminación de registros

## Tecnologías

- HTML5
- CSS3 con diseño tipo cuaderno/bitácora
- JavaScript vanilla (ES6 Modules, clases con herencia)
- Bootstrap 4
- jQuery (modales)
- Fetch API para carga de datos JSON
- Audio API para sonidos

## Arquitectura JS

```
assets/js/
├── clases/       → Clase base Animal + subclases (Chinchilla, Puma, Zorro, etc.)
├── CargarDatos.js → Carga inicial del JSON de especies
├── Crear.js       → Instanciación y validación
├── Renderizar.js  → Manipulación del DOM
├── Previsualizar.js → Preview en vivo
├── Mantencion.js  → Utilidades (eliminar, limpiar)
└── index.js       → Punto de entrada y event listeners
```
