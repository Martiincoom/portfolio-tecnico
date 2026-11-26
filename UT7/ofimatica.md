# 7.3 Documentación técnica y herramientas ofimáticas

## 1. Documentación técnica

La documentación técnica recoge información sobre el funcionamiento, configuración y mantenimiento de sistemas informáticos.

Existen diferentes tipos:

- **Manual de usuario:** explica cómo utilizar un programa o dispositivo.
- **Manual de administración:** recoge configuraciones y tareas de mantenimiento.
- **README:** presenta un proyecto y explica cómo utilizarlo.
- **Registro de incidencias:** recoge errores y sus soluciones.

## 2. Herramientas ofimáticas

Las herramientas ofimáticas permiten crear documentos, hojas de cálculo y presentaciones.

| Función | Microsoft Office | LibreOffice |
|---|---|---|
| Texto | Word | Writer |
| Hojas de cálculo | Excel | Calc |
| Presentaciones | PowerPoint | Impress |
| Bases de datos | Access | Base |

También existe Markdown, un lenguaje sencillo que permite crear documentación utilizando texto plano.

## 3. Markdown

Markdown utiliza símbolos para dar formato al texto:

| Símbolo | Función |
|---|---|
| `#` | Título principal |
| `##` | Subtítulo |
| `**texto**` | Negrita |
| `*texto*` | Cursiva |
| `-` | Lista |
| `[texto](url)` | Enlace |

### Ejemplo de Markdown

```markdown
# Mi documento

## Introducción

Este texto está en **negrita**.

- Primer elemento
- Segundo elemento
```

## 4. Conversión de documentos

Los archivos Markdown se pueden convertir a otros formatos utilizando herramientas como Pandoc.

Por ejemplo:

```bash
pandoc manual.md -o manual.docx
```

Este comando convierte un documento Markdown en un archivo Word.

> [!IMPORTANT]
> Markdown es especialmente útil para crear documentación técnica porque permite trabajar con texto, código y sistemas de control de versiones como Git.

## 5. Conclusión

Las herramientas ofimáticas facilitan la creación de documentos profesionales. Markdown es una alternativa ligera y práctica para elaborar documentación técnica.