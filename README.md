
---

## 🧠 ESTRATEGIAS AVANZADAS

| Estrategia | Explicación |
|------------|-------------|
| **Disparo preventivo** | No esperes a que los aliens estén cerca; dispara constantemente mientras te mueves |
| **Movimiento pendular** | Muévete de un lado a otro siguiendo el ritmo de la formación enemiga |
| **Atento a las esquinas** | Los enemigos bajan más rápido cuando llegan a los bordes; prepárate para esquivar |
| **Prioridad alta** | Elimina primero los enemigos que están más abajo (fila inferior), ya que disparan más |
| **Efecto de enfriamiento** | Tras disparar, tu cañón tiene un breve destello blanco; espera ese momento para planear tu siguiente movimiento |
| **Toque continuo vs toque rápido (móvil)** | Mantén pulsado ◀ o ▶ para moverte de forma fluida; no necesitas tocar repetidamente |

---

## 📱 ADAPTACIONES PARA MÓVIL

Esta versión incluye mejoras específicas para jugar en dispositivos táctiles:

- ✅ **Canvas responsivo**: se escala automáticamente al tamaño de la pantalla manteniendo la proporción original.
- ✅ **Botones táctiles grandes**: fáciles de pulsar, con feedback visual al presionar (cambian de color).
- ✅ **Movimiento continuo**: mantén pulsado ◀ o ▶ para mover la nave sin interrupción.
- ✅ **Disparo dual**: puedes disparar con el botón 🔥 o directamente tocando el área de juego.
- ✅ **Detección automática**: los botones aparecen solo si el dispositivo es táctil (aunque se pueden forzar).
- ✅ **Prevención de gestos**: evita el zoom accidental y el desplazamiento de la página mientras juegas.
- ✅ **Soporte multitáctil**: los controles funcionan incluso con varios dedos.

---

## 🎨 DETALLES VISUALES

- ✅ **Estrellas parpadeantes** en el fondo (intensidad dinámica)
- ✅ **Explosiones** al destruir enemigos o al recibir daño
- ✅ **Efecto de recarga** de la nave (aura blanca al final del cooldown)
- ✅ **Diferentes sprites** según el enemigo (morados vs verdes)
- ✅ **Diseño neón retro** con bordes brillantes

> Nota: Esta versión es completamente visual (sin audio), pero los efectos animados están diseñados para evocar la experiencia arcade clásica.

---

## ❓ PREGUNTAS FRECUENTES

**¿Puedo disparar más rápido si presiono muchas veces el botón de disparo?**  
No, el juego tiene un cooldown fijo para mantener el balance arcade. El cañón necesita recargarse ~0.2 segundos entre disparos.

**¿Por qué a veces los enemigos bajan de golpe?**  
Es su patrón de movimiento clásico: al tocar el borde derecho o izquierdo, la formación completa desciende una fila.

**¿Los enemigos pueden salirse de la pantalla?**  
No, tienen límites superior e inferior para mantener la jugabilidad justa.

**¿Hay niveles infinitos?**  
En esta versión básica solo hay un nivel de 8 enemigos. Al eliminarlos, ¡ganas la partida!

**¿Puedo jugar en móvil sin teclado externo?**  
¡Sí! Los botones táctiles están diseñados específicamente para eso. No necesitas teclado.

**¿Cómo evito que el zoom se active mientras juego?**  
El juego previene automáticamente el zoom con `touch-action: manipulation` y evita gestos predeterminados en los botones.

**¿Los botones táctiles funcionan en el navegador de escritorio?**  
Sí, marca la casilla *"Mostrar botones táctiles"* y podrás usar el ratón para pulsarlos (útil para pruebas o pantallas híbridas).

---

## 🛠️ REQUISITOS TÉCNICOS

- **Navegador**: Moderno (Chrome, Edge, Firefox, Safari, navegadores móviles)
- **Tecnologías**: HTML5 Canvas, CSS3, JavaScript ES6
- **Plataformas**:
  - Windows / macOS / Linux (con teclado o ratón)
  - Android (Chrome, Firefox, Edge)
  - iOS / iPadOS (Safari, Chrome)
- **Conexión a internet**: No requerida (juego local)

---

## 🧪 DATOS TÉCNICOS PARA CURIOSOS

| Parámetro | Valor |
|-----------|-------|
| Tamaño canvas base | 800 × 550 píxeles |
| Escalado | Responsivo (mantiene aspecto 800:550) |
| Fotogramas por segundo | ~60 FPS (requestAnimationFrame) |
| Velocidad de la nave | 6 px/frame |
| Velocidad bala jugador | 7 px/frame (hacia arriba) |
| Velocidad bala enemiga | 4.5 px/frame (hacia abajo) |
| Cooldown entre disparos | 12 frames (~0.2 s) |
| Cooldown disparo enemigo | 45 frames (~0.75 s) |
| Tipo de detección táctil | `ontouchstart`, `maxTouchPoints` |
| Eventos táctiles | `touchstart`, `touchend`, `touchcancel` con `passive: false` |

---

## 🌟 CRÉDITOS Y VERSIÓN

- **Inspiración**: Galaga (Namco, 1981) - Uno de los shoot 'em up más icónicos de la historia
- **Versión**: 2.0 - Edición responsiva con controles móviles y táctiles
- **Adaptación móvil**: Botones táctiles, canvas fluido, detección automática
- **Desarrollada con**: HTML5, CSS3, JavaScript puro (Canvas API)
- **Estilo visual**: Retro futurista con efectos de neón y explosiones

---

## 📜 CÓDIGO FUENTE

El juego completo está contenido en un único archivo HTML. Puedes:
1. Guardar el código como `galaga_movil.html`
2. Abrirlo con cualquier navegador moderno (escritorio o móvil)
3. ¡Jugar sin necesidad de internet ni instalación!

---

## 🎯 COMPARATIVA DE VERSIONES

| Característica | Versión clásica | Versión móvil responsiva |
|----------------|----------------|--------------------------|
| Controles teclado | ✅ | ✅ |
| Controles táctiles | ❌ | ✅ (botones + toque en canvas) |
| Canvas responsivo | ❌ (fijo) | ✅ (escala automática) |
| Detección dispositivo | ❌ | ✅ (automática + manual) |
| Movimiento continuo touch | ❌ | ✅ (mantener pulsado) |
| Previene zoom/scroll | ❌ | ✅ |

---

*¡Buena suerte, piloto! La flota confía en ti. Destruye a los Galagans desde cualquier dispositivo y conviértete en una leyenda.* 🔥

---

**¿Listo para despegar?** Abre el juego, elige tu modo de control y ¡a disparar!
