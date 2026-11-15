# CV — Luis Fernando Romero Amasifuen

Currículum Vitae en formato web responsivo y optimizado para impresión/exportación a PDF (A4).

## Estructura del proyecto

```text
cv/
├── index.html      # Estructura semántica del CV
├── styles.css      # Estilos de pantalla, diseño responsivo e impresión A4
├── img/
│   └── foto.jpeg   # Fotografía de perfil
├── .gitignore
└── README.md
```

## Características

- **Diseño limpio y profesional:** Presentación tipo hoja A4 centrada en pantalla.
- **Exportación a PDF:** Botón **Imprimir / Guardar PDF** en la vista web y reglas `@media print` para generar un PDF A4 sin elementos de interfaz innecesarios.
- **Responsivo:** Adaptado para escritorio, tablet y móvil.
- **100% estático:** Listo para publicar directamente en GitHub Pages sin dependencias externas ni paso de compilación.

## Vista previa local

Abre `index.html` directamente en tu navegador o levanta un servidor local simple:

```bash
python -m http.server 8000
```

Luego visita `http://localhost:8000`.
