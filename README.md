# 🌌 Star Wars: Los Bandos de la Galaxia

Una página web temática desarrollada con **HTML5** y **CSS3** que presenta una comparativa visual entre **El Imperio Galáctico** y **La Alianza Rebelde**, aplicando estilos avanzados como texturas espaciales, tipografías personalizadas y efectos de iluminación (*glow/drop-shadow*).

---

## 🚀 Características

* **Diseño Temático Retro-Espacial:** Fondo de galaxia con tipografía futurista.
* **Estilos por Bando:**
  * **El Imperio (Lado Oscuro):** Resplandores rojos y fuentes emblemáticas (`Tie Wing`).
  * **Los Rebeldes (Jedi):** Resplandores verdes estilo sable de luz y fuente icónica (`StarJedi`).
* **Soporte de Fuentes Externas:** Uso de Google Fonts (`Orbitron`, `Russo One`) y fuentes personalizadas cargadas mediante `@font-face`.
* **Efectos CSS:** Uso de `filter: drop-shadow()` y `text-shadow` para simular el brillo del neón y la Fuerza.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructuración semántica de elementos, listas e imágenes.
* **CSS3:** 
  * Declaración de `@font-face` e importación de fuentes desde Google Fonts.
  * Sombras avanzadas (`drop-shadow`, `text-shadow`).
  * Selectores de clase e ID para personalización por facción.

---

## 📂 Estructura del Proyecto

```text
.
├── index.html        # Estructura principal del sitio web
├── style.css         # Hoja de estilos con efectos y tipografías
├── Fonts/            # Fuentes personalizadas (.ttf)
│   ├── TieWing-y0Ee.ttf
│   └── SfDistantGalaxy-0l3d.ttf
└── img/              # Imágenes locales (escudos y vehículos)
    ├── imperio_escudo.png
    ├── rebelde_escudo.png
    └── Tanque_asalto.png
