# Diseño de protocolos, código y datos abiertos

Este repositorio contiene los materiales de la presentación **“Diseño de protocolos, código y datos abiertos”**, preparada para el [**Workshop Abre tu Ciencia**](https://atc26.com).

El objetivo del proyecto es **mostrar, mediante un ejemplo real**, buenas prácticas para diseñar repositorios científicos que sean:
- ejecutables,
- comprensibles,
- reutilizables,
- y alineados con principios de ciencia abierta (FAIR).

---

## 🔍 ¿Qué hay en este repositorio?

- Una presentación en formato **Reveal.js**, generada con **Quarto**
- Ejemplos visuales y conceptuales sobre:
  - código ejecutable,
  - datos abiertos y *machine-readable*,
  - principios FAIR aplicados en la práctica
- Un repositorio organizado para servir como **ejemplo didáctico de buen README**

🖥️ **Presentación en línea:**  
👉 https://jdleongomez.github.io/protocolos_codigo_y_datos_abiertos/

---

## ▶️ Cómo usar este repositorio

### Opción 1: Ver la presentación (recomendado)
No necesitas instalar nada.

Abre directamente:  
https://jdleongomez.github.io/protocolos_codigo_y_datos_abiertos/

### Opción 2: Generar la presentación localmente

Requisitos:
- R (≥ 4.2)
- Quarto (≥ 1.4)

Pasos mínimos:

```bash
git clone https://github.com/jdleongomez/protocolos_codigo_y_datos_abiertos.git
cd protocolos_codigo_y_datos_abiertos
quarto render index.qmd
```

## 🗂️ Estructura del repositorio

```text
├── index.qmd                                 # Fuente principal de la presentación (Quarto)
├── index.html                                # Presentación renderizada (Reveal.js)
├── index_files/                              # Dependencias HTML generadas automáticamente
├── css/                                      # Estilos personalizados
├── images/                                   # Imágenes usadas en las diapositivas
├── _extensions/                              # Extensiones de Quarto (clean-revealjs)
├── mathjax-config.js                         # Configuración de MathJax
├── protocolos_codigo_y_datos_abiertos.Rproj  # Proyecto RStudio
├── README.md                                 # Descripción y guía del repositorio
├── LICENSE                                   # Licencia del contenido (CC BY 4.0)
├── CITATION.cff                              # Información de citación (FAIR)
├── CODE_OF_CONDUCT.md                        # Código de conducta
└── CONTRIBUTING.md                           # Guía mínima de contribución 
```

Notas:
- `index.qmd` es el único archivo que debe editarse para cambiar el contenido.
- `index.html`, `index_files/` y `README.html` son archivos generados automáticamente.
- Los archivos `LICENSE`, `CITATION.cff`, `CODE_OF_CONDUCT.md` y
  `CONTRIBUTING.md` ilustran buenas prácticas de ciencia abierta.

## 🔄 Estado del proyecto

* Estado: estable  
* Mantenimiento: no activo  
* Propósito: material docente y de referencia

Este repositorio no está pensado para desarrollo continuo, sino como ejemplo reproducible.

## 🤝 Contribuciones y reutilización

No se esperan contribuciones directas, pero eres libre de:

* reutilizar la estructura del repositorio,
* adaptar el README,
* usar fragmentos del código o de la presentación con fines docentes.

Si encuentras errores o deseas comentar algo, puedes abrir un issue.

## 📎 Información adicional

Este repositorio incluye una licencia abierta (CC BY 4.0), un código de conducta
y una guía mínima de citación y reutilización.

## 👤 Autor

Juan David Leongómez
<https://jdleongomez.info/es/>

Workshop Abre tu Ciencia
<https://atc26.com>