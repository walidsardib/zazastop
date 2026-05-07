# ZazaStop · Web

Sitio web del restaurante **ZazaStop** — tacos franceses y Crousty en Zaragoza.
Av. de Madrid 162 · Las Delicias · Zaragoza.

Construido con [Astro](https://astro.build) + TypeScript. Datos de menú e
imágenes de producto extraídos del listing público de Glovo.

## Estructura

```
zazastop/
├── web/                 # proyecto Astro (sitio público)
│   ├── src/
│   │   ├── components/  # Nav, Hero, Story, Spotlight, Menu, Visit, Footer
│   │   ├── layouts/     # Layout.astro
│   │   ├── pages/       # index.astro
│   │   ├── styles/      # global.css (paleta de marca)
│   │   └── products.json
│   └── public/images/
│       ├── brand/       # logo + banner
│       └── products/    # 30 imágenes de producto
├── public/images/       # copia maestra de imágenes (fuente)
└── scraper/             # datos crudos + script de extracción Glovo
```

## Marca

| Token            | Color        |
| ---------------- | ------------ |
| `--purple`       | `#5742A7`    |
| `--purple-deep`  | `#3D2D7A`    |
| `--purple-light` | `#7A63D4`    |
| `--yellow`       | `#FFD23F`    |
| `--orange`       | `#FF7A1A`    |
| `--cream`        | `#FFF8EC`    |
| `--ink`          | `#1A1330`    |

Fuente principal: **Archivo Black** (titulares) + **Inter** (cuerpo).

## Desarrollo

```bash
cd web
npm install
npm run dev      # http://localhost:4321
npm run build
npm run preview
```

## Datos

- Menú e imágenes: [Glovo · Zaza Stop Zaragoza](https://glovoapp.com/es/es/zaragoza/stores/zaza-stop-zaragoza)
- Instagram: [@zazastop_](https://www.instagram.com/zazastop_/)

## Créditos

- Restaurante: ZazaStop (Ibra · Mayu · Nilmar)
- Sitio: scaffolding inicial generado con Claude Code
