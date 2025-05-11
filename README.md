# 🧠 Procesamiento de Imágenes con Filtros Manuales en Python

Este proyecto implementa desde cero dos técnicas fundamentales de procesamiento digital de imágenes utilizando Python y NumPy, sin recurrir a funciones de filtrado predefinidas.

---

## 🔧 Filtros implementados

### 1. 🪓 Filtro de Repujado (Emboss)

Se aplica un kernel manual mediante convolución directa sobre cada canal RGB de una imagen, resaltando bordes y contornos para simular un efecto de relieve.

- Convolución implementada desde cero.
- Operación separada por canal (R, G, B).
- Visualización antes y después del filtro.

### 2. 🔍 Detección de Bordes con Segunda Derivada

Se aproxima la segunda derivada de la brillantez en imágenes en escala de grises usando diferencias finitas:

- **Ai:** promedio local de intensidad.
- **Fi:** primera diferencia promedio.
- **Si:** segunda diferencia promedio.
- Derivadas calculadas en dirección horizontal y vertical.
- Combinación para obtener el mapa de bordes final.

---

## 🖼️ Imágenes utilizadas

- Imagen de un integrante del grupo (`Sergio_Bohada.jpeg`).
- Imagen de un gato con alto contraste (`cat_test.jpg`).

---

## ▶️ Cómo ejecutar

1. Clona el repositorio:

```bash
git clone https://github.com/tuusuario/procesamiento-imagenes-manual.git
cd procesamiento-imagenes-manual
```
