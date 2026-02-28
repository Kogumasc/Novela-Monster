# Novela Monster

Repositorio de trabajo para la novela web **Monster**. Aquí se gestiona el proceso creativo: guía de estilo del autor, fichas de personajes, notas de ambientación y los capítulos en desarrollo.

## Estructura del repositorio

```
Novela-Monster/
├── README.md               # Este archivo
├── GUIA_DE_ESTILO.md       # Guía del estilo de escritura del autor
├── capitulos/
│   ├── PLANTILLA_CAPITULO.md   # Plantilla para nuevos capítulos
│   └── capXX_titulo.md         # Capítulos (ej. cap01_el_inicio.md)
├── personajes/
│   └── PERSONAJES.md       # Fichas de los personajes principales y secundarios
└── mundo/
    └── AMBIENTACION.md     # Notas de ambientación y construcción del mundo
```

## Flujo de trabajo para escribir capítulos

1. **Define el estilo** – Completa `GUIA_DE_ESTILO.md` con ejemplos de tu prosa, preferencias narrativas y recursos literarios que usas habitualmente.
2. **Registra personajes** – Añade o actualiza las fichas en `personajes/PERSONAJES.md` antes de escribir un capítulo nuevo.
3. **Describe el capítulo** – Abre un _issue_ o comenta en el PR con:
   - Título tentativo
   - Tono general (acción, introspección, misterio, etc.)
   - Puntos clave que deben ocurrir
   - Personajes presentes
4. **Redacción asistida** – Con esa información y la guía de estilo, el agente redactará un borrador del capítulo respetando tu voz.
5. **Revisión** – Revisa el borrador, solicita ajustes y aprueba el capítulo final.

## Convenciones de nomenclatura

| Tipo de archivo | Formato |
|---|---|
| Capítulo | `cap01_nombre_del_capitulo.md` |
| Personaje nuevo | sección en `PERSONAJES.md` |
| Nota de mundo | sección en `AMBIENTACION.md` |
