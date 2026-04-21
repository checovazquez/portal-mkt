# Portal MKT MASECA

Hub central de dinamicas y activaciones para eventos de MASECA Autoservicios.

## Estructura del repo

```
maseca-portal-mkt/
├── index.html      # Pagina principal del portal
├── styles.css      # Estilos
└── README.md
```

## Juegos incluidos

| Juego | Repo | URL |
|-------|------|-----|
| Gana con MASECA | checovazquez/GanaConMASECA | https://checovazquez.github.io/GanaConMASECA/ |
| Rompe-MASECAS | checovazquez/rompe-cabezas | https://checovazquez.github.io/rompe-cabezas/ |

## Agregar un nuevo juego

1. Abre `index.html`
2. Copia el bloque de una tarjeta existente dentro de `#games-grid`
3. Actualiza: titulo, descripcion, tags, href del `<a>`, y los colores CSS variables `--accent` e `--icon-bg`
4. Cambia o elimina la clase `card-coming` cuando el juego este listo

## Colores MASECA

```css
--green:  #00843D
--yellow: #FFD200
```

## Deploy

Este repo usa GitHub Pages. Activa Pages desde **Settings > Pages > Branch: main / root**.

La URL quedara en: `https://checovazquez.github.io/maseca-portal-mkt/`
