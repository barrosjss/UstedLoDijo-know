# Capítulos

Una carpeta por capítulo: `<nn>-<slug>/`

```
capitulos/01-cobrar-barato/
├── brief.md        ← plantillas/brief-tema.md
├── guion.md        ← plantillas/guion-capitulo.md
├── acta.md         ← plantillas/acta-de-cierre.md
└── notas/
    ├── clips.md    ← marcas del productor (mm:ss — quién — de qué)
    └── chatgpt.png ← captura de la respuesta, si hubo sección de IA
```

Los archivos de audio y video **no van en el repo** (ver `.gitignore`). Viven en el
disco + la nube, con la nomenclatura `ULD-<nn>-<slug>/` descrita en
[producción](../docs/06-produccion.md).

Los temas aprobados que todavía no tienen capítulo asignado esperan en `temas/`.
