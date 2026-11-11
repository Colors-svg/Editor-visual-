# Editor Visual JSON · SharePoint / Lists · UdeA

Generador visual de JSON para formato condicional de **SharePoint / Microsoft Lists** con identidad institucional de la **Universidad de Antioquia**. Sin dependencias de red, 100 % local.

Abrir `index.html` en el navegador o servir la carpeta con GitHub Pages.

## Módulos

1. **Reglas por clases Fluent** — condiciones encadenadas `Y / O` con prioridad que generan `additionalRowClass` (fila) o `class` (columna) con cascadas `if(...)` rigurosas.
2. **Columna custom (píldoras CSS)** — geometría, iconos, colores texto/fondo/borde por regla, simulación en vivo y `column-formatting` con estilos inline.

## Uso en SharePoint

1. Configura reglas, estilos y (módulo 2) geometría.
2. Expande y copia el JSON (`Copiar JSON`).
3. En la lista: *Configuración → Formato → Pegar JSON avanzado* (vista para filas, columna para píldoras).

## Funciones

- Validación en vivo con avisos, saneo de importados y red de seguridad (último JSON válido).
- Exportar/importar configuración, persistencia local, JSON expandible.
- Iconos Lucide embebidos, escudo UdeA vectorizado, tipografías auto-hospedadas (`fonts/`: Inter, Roboto Slab, JetBrains Mono).

## Estructura

```
index.html                  App monofichero (lógica + estilos)
fonts/                      Tipografías woff2 latin (Inter, Roboto Slab, JetBrains Mono)
udea-escudo.svg             Escudo vectorizado (respaldo)
diseno-editor-figcraft.figcraft  Diseño en FigCraft (sistema del Manual de Marca)
```

Paleta: [Paleta-Udea](https://github.com/Colors-svg/Paleta-Udea) · Verde institucional `#026937`.
