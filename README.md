# Flores Amarillas para Ti

Una animación web interactiva donde un ramo de flores amarillas se dibuja a mano, tallo por tallo, flor por flor, hasta revelar el mensaje final.

---

## Link de Github Pages

<!-- Pon aquí tu enlace cuando lo tengas disponible -->
> **[https://velvett1521.github.io/Flores_amarillas/](#)**

---

## 🛠️ Tecnología

- HTML5 Canvas (dos capas: flores + texto)
- JavaScript vanilla, sin dependencias
- Fuentes: [Dancing Script](https://fonts.google.com/specimen/Dancing+Script) + [Quicksand](https://fonts.google.com/specimen/Quicksand) vía Google Fonts

---

## ⚙️ Ajustes rápidos

Todos los valores clave están al inicio del `<script>` en `index.html`:

| Variable | Dónde | Qué controla |
|---|---|---|
| `NUM_FLOWERS` | config | Número de flores |
| `SPREAD` | `initFlowers()` | Amplitud del abanico (radianes) |
| `distFactor` por ring | `initFlowers()` | Separación entre anillos |
| `STEM_DUR` | cada flor | Velocidad de crecimiento del tallo |
| `BLOOM_DUR` | cada flor | Velocidad de floración |
| `delay` | cada flor | Desfase entre flores (`i * N`) |
| `CHAR_DELAY` | config | Velocidad del texto (frames por letra) |
| `S` (escala) | `resize()` | Tamaño general — divide `min(W,H)` entre este número |

---

## 📁 Archivos

```
index.html   ← todo el proyecto en un solo archivo
README.md    ← este archivo
```

---

## 📄 Uso

Solo abre `index.html` en cualquier navegador moderno. No requiere servidor ni instalación.