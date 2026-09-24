# 🎯 Tactical Strike

> Shooter táctico HTML5 · desarrollo por versiones · releases automáticos

![badge](https://img.shields.io/badge/estado-en%20desarrollo-fbbf24)
![badge](https://img.shields.io/badge/versión-v0.1.0-38bdf8)
![badge](https://img.shields.io/badge/tecnología-HTML%20CSS%20JS-0f172a)

Tactical Strike es un juego de disparos táctico en navegador, inspirado en la intensidad de los shooters competitivos. La idea del proyecto es crear una experiencia rápida, técnica y muy jugable, con una estructura pensada para crecer por versiones: mejoras, nuevos modos, nuevas armas, mapas y contenido premium en cada release.

## Objetivo del juego

- Rangos de combate rápidos
- Movimiento fluido y control directo
- Enemigos agresivos y progresivos
- Sistema de puntuación y oleadas
- Estética minimalista y táctica

## Cómo jugar

1. Abre `index.html` en tu navegador o usa un servidor local.
2. Mueve al personaje con `WASD` o flechas.
3. Apunta con el ratón.
4. Dispara con clic izquierdo o `Espacio`.
5. Sobrevive oleadas y gana puntos.

```bash
python3 -m http.server 8000
```

Después entra a:

```text
http://localhost:8000
```

## Estructura del proyecto

```text
Tactical Strike/
├── .github/
│   └── workflows/
│       ├── pages.yml
│       └── release.yml
├── assets/
│   └── README.md
├── versions/
│   ├── README.md
│   └── v0.1.0/
│       ├── README.md
│       ├── index.html
│       └── style.css
├── releases/
│   └── README.md
├── index.html
├── style.css
├── game.js
├── LICENSE
├── README.md
└── .gitignore
```

## Versionado

Se usarán versiones semánticas:

- `v0.1.0` = primera build jugable
- `v0.2.0` = mejoras del gameplay
- `v0.3.0` = nuevas armas y sistemas
- `v1.0.0` = versión estable pública

Cada versión queda almacenada en la carpeta `versions/` con su propio README y snapshot.

## Releases

Cuando se publique un tag como `v0.2.0`, el workflow de GitHub Actions genera un ZIP descargable y un Release en GitHub con ese paquete.

```bash
git tag v0.2.0
git push origin v0.2.0
```

## Roadmap

### v0.1.0
- Movimiento básico
- Disparo y apuntado
- Enemigos básicos
- Vida y puntuación
- Oleadas

### v0.2.0
- Menú inicial
- Nuevos enemigos
- Mejoras visuales
- Efectos de sonido

### v0.3.0
- Sistema de armas
- Balance y habilidades
- Mapas con cobertura

### v1.0.0
- Modo competitivo
- Pulido final de juego
- Mejor experiencia y estabilidad

## Licencia

MIT
