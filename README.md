## Prueba Técnica en Tiempo Real – Memory Game con React

### Objetivo
Desarrollar un juego de memory utilizando React en el que el usuario deba hacer coincidir pares de cartas.

---

### Instrucciones para el entrevistado
- Tendrás **una hora** para desarrollar la prueba.
- Puedes usar **ChatGPT, documentación o cualquier otro recurso online**.
- Puedes hacer preguntas durante el proceso.
- **Opcional:** Puedes usar TypeScript si lo prefieres.
- El código debe estar estructurado y ser fácil de leer.
- Assets:  
```javascript
    const images = ["https://images.unsplash.com/photo-1626808642875-0aa545482dfb",
    "https://images.unsplash.com/photo-1546842931-886c185b4c8c",
    "https://images.unsplash.com/photo-1520763185298-1b434c919102",
    "https://images.unsplash.com/photo-1442458017215-285b83f65851",
    "https://images.unsplash.com/photo-1496483648148-47c686dc86a8",
    "https://images.unsplash.com/photo-1591181520189-abcb0735c65d",
    "https://images.unsplash.com/photo-1468327768560-75b778cbb551",
    "https://images.unsplash.com/photo-1519378058457-4c29a0a2efac"];
  ```

---

### Requisitos del juego
1. **Tablero de juego:**
   - Se generará un grid de 4x4 (16 cartas en total).
   - Las cartas estarán ocultas al inicio y se revelarán al hacer clic.
   - Cada carta tendrá un par idéntico.

2. **Lógica del juego:**
   - Al hacer clic en una carta, se muestra su contenido.
   - Si se seleccionan dos cartas y son iguales, permanecen visibles.
   - Si no coinciden, se ocultan tras un breve tiempo (ej. 1 segundo).
   - El juego termina cuando todas las cartas han sido emparejadas.

3. **Estado del juego:**
   - Contador de intentos o tiempo transcurrido.
   - Mensaje de "¡Felicidades, has ganado!" cuando finaliza el juego.

---

### Extras opcionales (si hay tiempo)
- Optimización de renders
- Un botón de "Reiniciar" que resetee el juego.
- Animaciones CSS para revelar las cartas.

---

### Seguimiento de la entrevista
⏱ **Tiempo estimado: 60 min**
1. **(5 min)** Presentación y preguntas iniciales.
2. **(45 min)** Desarrollo del juego con orientación mínima.
3. **(10 min)** Revisión del código y preguntas técnicas sobre decisiones tomadas.
