# ZazaStop · Web

Sitio web del restaurante **ZazaStop** — tacos franceses y Crousty en Zaragoza.
Av. de Madrid 162 · Las Delicias · Zaragoza.

Construido con [Astro](https://astro.build) + TypeScript.

## Estructura

```
zazastop/
├── astro.config.mjs
├── package.json
├── tsconfig.json
├── public/
│   ├── favicon.svg
│   └── images/
│       ├── brand/      # logo + banner
│       ├── ig/         # carta1/2/3 (fondos checker oficiales)
│       └── products/   # 30 imágenes producto
├── src/
│   ├── components/     # Nav, Hero, Spotlight, Menu, Builder, Pricing, Story, Visit, Footer
│   ├── layouts/        # Layout.astro
│   ├── pages/          # index.astro
│   ├── styles/         # global.css
│   └── products.json   # menú con precios oficiales en tienda
└── scraper/            # data Glovo (referencia)
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

Fuente: **Archivo Black** (titulares) + **Inter** (cuerpo).

## Desarrollo

```bash
npm install
npm run dev      # http://localhost:4321
npm run build    # output: dist/
npm run preview
```

## Despliegue

Build estático en `dist/`. Compatible con cualquier hosting estático
(Cloudflare Pages, Netlify, Vercel, GitHub Pages…). Comando de build:
`npm run build`. Output dir: `dist`.

## Datos

- Carta + precios: tomados de la propia carta oficial del local.
- Imágenes producto: extraídas del listing público de Glovo.
- Instagram: [@zazastop_](https://www.instagram.com/zazastop_/)
- Glovo: [Zaza Stop Zaragoza](https://glovoapp.com/es/es/zaragoza/stores/zaza-stop-zaragoza)
