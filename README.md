# portfolio-media

Videos en alta del portfolio de Enzo Zingaretti
([enzo-diaz-zingaretti.vercel.app](https://enzo-diaz-zingaretti.vercel.app)).
Viven acá y no en el repo del sitio para que ese no cargue cientos de MB de video.

- `1080/` — lado corto hasta 1080 px (desktop), H.264 CRF 19, sin audio.
- `720/` — lado corto hasta 720 px (celular), H.264 CRF 21, sin audio.
- `1080/**/*-poster.jpg` — el cuadro de portada de cada video.

Cada archivo tiene el mismo camino que su versión liviana en `public/` del sitio
(`/images/reels/kook.mp4` → `1080/images/reels/kook.mp4`). La lista de qué videos
tienen versión en alta está en `src/media.js` del sitio. Los originales están en el
Drive (`reels portfolio`, `PORTFOLIO`, `PROYECTOS`).

Sin build: Vercel publica los archivos tal cual.
