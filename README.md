#  Deathbat Game

Videojuego de plataformas 2D desarrollado con **HTML, CSS y JavaScript**, utilizando el elemento `<canvas>` para el renderizado. Puedes probar el juego en el siguiente link: https://sensational-babka-fb7642.netlify.app

---

##  Descripción

**Deathbat Game** es un videojuego de plataformas donde el jugador controla a un personaje animado que debe esquivar enemigos, saltar obstáculos y sobrevivir el mayor tiempo posible. El proyecto fue creado con fines educativos y de práctica en desarrollo web y lógica de videojuegos.

Incluye mecánicas como:
- Movimiento lateral
- Salto y doble salto
- Colisiones
- Sistema de vidas
- Enemigos
- Invencibilidad temporal al reaparecer
- Animaciones con sprites/GIF

---

## Tecnologías utilizadas

- **HTML5** – Estructura base
- **CSS3** – Estilos del juego e interfaz
- **JavaScript (ES6)** – Lógica del juego
- **Canvas API** – Renderizado gráfico

---

## Estructura del proyecto

```
DeathbatGame/
│
├── index.html
├── assets/
│   ├── player.gif
│   ├── enemies/
│   ├── background.png
│   └── sounds/
└── README.md
```

---


## Controles del juego

| Tecla | Acción |
|-------|--------|
| ← | Mover a la izquierda |
| → | Mover a la derecha |
|  Espacio | Saltar |
| Espacio (en el aire) | Doble salto |

---

## Mecánicas implementadas

### ✔ Movimiento del jugador
Sistema de velocidad horizontal y gravedad.

### ✔ Salto y doble salto
Permite un segundo salto en el aire antes de tocar el suelo.

### ✔ Colisiones
Detección rectangular entre jugador y enemigos.

### ✔ Sistema de vidas
El jugador pierde una vida al colisionar con un enemigo.

### ✔ Invencibilidad temporal
Al reaparecer, el jugador obtiene invulnerabilidad con efecto de parpadeo.

### ✔ Enemigos
Movimiento automático y reinicio de posición.

### ✔ Animaciones
Uso de imágenes animadas (GIF o sprites).

---

## Flujo general del juego

1. Inicialización del canvas
2. Carga de assets
3. Loop principal (`requestAnimationFrame`)
4. Actualización de posiciones
5. Detección de colisiones
6. Renderizado

---


## Solución de problemas comunes

### La animación GIF no se reproduce
Verifica que se esté usando `drawImage()` correctamente y que el objeto `Image()` esté cargado.

### El jugador atraviesa el suelo
Revisar lógica de colisiones verticales y gravedad.

### El doble salto se activa infinitamente
Asegurar contador de saltos y reinicio al tocar el suelo.

---

## Autor

Josué Alejandro Huesca Laureano

---

## 📄 Licencia

Este proyecto es de uso educativo y personal. Puedes modificarlo libremente.
