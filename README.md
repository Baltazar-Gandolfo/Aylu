# 🌸 Feliz Cumple, Aylu

Página web interactiva de cumpleaños para Aylu, hecha con amor por Baltazar.

Es una sola página (`index.html`) pensada para el teléfono: un recorrido por
pétalos de flor, con cosas para tocar, fotos, música de Taylor Swift y, en el
centro, la sorpresa del regalo (un fin de semana de spa).

## Cómo verla

Abrí `index.html` en el celular. Para compartirla con Aylu por un link, se puede
publicar gratis con **GitHub Pages** (Settings → Pages → Branch) o cualquier
hosting estático.

## Cómo agregar tus cosas (fotos, video y canción)

Todo funciona aunque estos archivos no estén todavía (se ven lugares con 📷/🎬).
Cuando quieras que aparezcan las cosas reales, sumá los archivos con **estos
nombres exactos**:

### 📷 Fotos
Poné 4 fotos en la carpeta `fotos/`:
```
fotos/foto1.jpg
fotos/foto2.jpg
fotos/foto3.jpg
fotos/foto4.jpg
```

### 🎬 Video
Poné un video en la carpeta `video/`:
```
video/video.mp4
```

### 🎵 Canción de Taylor
Poné el audio en la carpeta `musica/`:
```
musica/cancion.mp3
```

> Tip: usá archivos livianos (fotos < 1 MB, video corto) para que cargue rápido
> en el teléfono.

## Personalizar textos

Los mensajes están en `index.html`. Se pueden editar:
- Las notas de los pétalos (buscá `var notas` dentro del `<script>`).
- La frase de Taylor (buscá `class="lyric"`).
- El detalle del regalo (buscá `class="premio"`).
- El mensaje final y la firma (última sección).
