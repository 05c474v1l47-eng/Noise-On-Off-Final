Bloques de Texto: Fragmentación Digital y Ruido

## 📢 Descripción de la Obra

Este repositorio contiene el código fuente de **"Bloques de Texto"**, una obra de arte digital conceptual que utiliza la sintaxis y la estética del código para explorar temas de **ruido, desolación, y desintegración del lenguaje**.

La pieza presenta un flujo de texto experimental y fragmentado, intercalado con palabras clave destacadas y bloques de ruido digital (caracteres aleatorios). Conceptualmente, simula la interferencia, el colapso de la comunicación y la **entropía en el dominio textual y sonoro**.

## ✨ Funcionalidad Interactiva

La pieza está diseñada para ser un punto de quiebre sonoro y visual:

* **Activación Glitch:** El efecto principal se activa al hacer clic en la palabra clave **"DESOLACIÓN"**.
* **Efecto Sinestésico:** Al activarse, el código desencadena simultáneamente dos efectos:
    1.  **Visual:** El cuerpo del texto cambia de color y aplica una animación CSS de *glitch* (parpadeo y distorsión sutil del texto).
    2.  **Sonoro:** Se reproduce una pista de *noise* (palabras habladas, ruido blanco/sonido ambiental) para generar una experiencia sinestésica de saturación de la información.
* **Audio *Responsive*:** El JavaScript incluye una lógica de *unlock* (desbloqueo) para asegurar que el componente de audio pueda reproducirse en navegadores móviles y dentro de entornos de *iframe* (como Wix), superando las restricciones de reproducción automática.

## 🛠️ Tecnologías Usadas

El proyecto está diseñado como un único archivo autocontenido para una fácil incrustación:

* **HTML:** Estructura del texto narrativo, con etiquetas `<strong>` utilizadas para conceptualizar y marcar las palabras clave.
* **CSS (`<style>`):** Define los estilos del cuerpo del texto, la interactividad del *trigger*, y la animación clave (`@keyframes`) que crea el efecto visual Glitch.
* **JavaScript (`<script>`):** Contiene la lógica para alternar el estado Glitch (`toggleGlitch`) y el script esencial para el manejo y desbloqueo del elemento `<audio>` en diferentes plataformas.

## 🔗 Estructura del Archivo

La pieza es un solo archivo HTML que integra CSS, JavaScript y el contenido textual para su implementación directa en cualquier componente de código web (ej: Componente HTML de Wix).

---

## ⚖️ Licencia

Este proyecto está bajo la Licencia MIT

---
