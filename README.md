# Jaque Matemático

Plataforma web accesible para aprender matemáticas con el ajedrez, pensada para estudiantes ciegos y con baja visión de la I.E.T. José Eugenio Martínez (Valledupar, Cesar).

Proyecto pedagógico de la Licenciatura en Matemáticas, Universidad Popular del Cesar, 2026-II.
Autores: Martín Camilo Pacheco Córdoba y Luis David Delgado López.

## Contenido

- `index.html`: la página completa, con las audiodescripciones grabadas incorporadas.
- `stockfish-19-lite-single.js` y `stockfish-19-lite-single.wasm`: motor Stockfish 19 lite (2026) con red neuronal NNUE (stockfish.js de Nathan Rugg / Chess.com, GPLv3). Mide las jugadas del estudiante y juega como rival graduado por ciclo.
- `stockfish-19-asm.js`: el mismo Stockfish 19 en JavaScript puro, solo de respaldo si el navegador no admite WebAssembly.
- `LICENSE-stockfish.txt`: licencia GPLv3 del motor.

Los archivos del motor deben quedar junto a `index.html`.

## Cómo verla

Publicada con GitHub Pages, o en local con:

```
python -m http.server 8000
```

y abriendo `http://localhost:8000`.
