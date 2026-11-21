# Especificaciones Técnicas de Sprites — `pokeemerald-expansion` 1.17.1

Verificado directamente en `graphics/pokemon/` y `graphics/object_events/pics/people/` del repositorio:

## 1. Sprites de Pokémon
- **Sprite frontal animado (`anim_front.png`):** 64 × 128 px (2 frames de 64 × 64 px apilados verticalmente).
- **Sprite trasero (`back.png`):** 64 × 64 px.
- **Icono de PC/Equipo (`icon.png`):** 32 × 64 px (2 frames de 32 × 32 px apilados verticalmente).
- **Huella (`footprint.png`):** 16 × 16 px (1bpp).
- **Paletas (`normal.pal`, `shiny.pal`):** Formato JASC-PAL, 16 colores (4bpp), índice 0 = color de fondo transparente.
- **Overworld (`overworld.png`):** Hoja de sprites de 16×16 / 32×32 según tamaño de la especie, con `overworld_normal.pal` y `overworld_shiny.pal`.

## 2. Sprites de Protagonistas
- **Overworld (`graphics/object_events/pics/people/`):** Hojas de animación separadas para caminar, correr, bicicleta, surf, pesca y regadera/acciones, en formato 16×32 px por frame (4bpp, 16 colores).
- **Entrenador frontal (`graphics/trainers/front_pics/`):** 64 × 64 px.
- **Entrenador trasero (`graphics/trainers/back_pics/`):** 64 × 64 px (con frames de lanzamiento de Poké Ball).
