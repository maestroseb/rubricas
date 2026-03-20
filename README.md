# RubricApp

Crea y evalua rubricas interactivas en segundos. Pega tus datos desde cualquier fuente y genera una rubrica lista para evaluar.

**Sin registro. Sin backend. Todo en tu navegador.**

---

## Que hace

1. **Pegas** los datos de tu rubrica (desde ChatGPT, Excel, Sheets, Markdown...)
2. **Generas** la rubrica con niveles, puntos y pesos detectados automaticamente
3. **Evaluas** haciendo clic o con el teclado
4. **Exportas** notas, resumen y PDF

Un solo archivo HTML. Sin dependencias. Funciona offline.

---

## Funcionalidades

### Entrada inteligente
- Pega desde **cualquier fuente**: ChatGPT, Gemini, Excel, Google Sheets, Markdown, tablas HTML
- Detecta automaticamente el formato (tabulaciones, CSV, pipes, texto concatenado)
- Extrae niveles y puntuaciones del encabezado (ej: `Excelente (4)`)
- Vista previa editable celda a celda antes de generar

### Evaluacion interactiva
- Clic en un nivel para puntuar, clic otra vez para deseleccionar
- **Puntuacion en tiempo real**: anillo animado con nota sobre 10 y calificacion automatica
- Pesos personalizables por indicador con redistribucion inteligente
- Desglose visual por criterio con codigo de color

### Navegacion por teclado
| Tecla | Accion |
|-------|--------|
| `1-9` | Seleccionar nivel por puntuacion |
| `Enter` | Siguiente indicador (o siguiente alumno) |
| Flechas arriba/abajo | Moverse entre indicadores |
| Flechas izquierda/derecha | Cambiar de alumno |

### Multi-alumno
- Crea listas de alumnos por grupo (ej: "3.o A ESO")
- Activa varias listas a la vez para clases combinadas
- Barra de navegacion con puntos de progreso (verde = evaluado)
- Cada alumno conserva su evaluacion al navegar

### Criterios de evaluacion
- Campo dedicado para codigos curriculares (ej: `LCL.3.1.2, CE.3`)
- Autodeteccion de codigos en los datos pegados (CE, CCL, STEM, CD, CPSAA...)
- Aparecen en la rubrica, el resumen, al copiar y en el PDF

### Resumen y exportacion
- **Resumen con pestanas**: tabla de todos los alumnos con nota, calificacion y media
- **Copiar**: pega directamente en Excel/Sheets (formato TSV con columnas por indicador)
- **PDF individual**: imprime la rubrica evaluada de un alumno
- **PDF completo**: tabla resumen por grupo + rubrica individual de cada alumno evaluado

### Biblioteca local
- Guarda hasta 20 rubricas con todos sus datos
- Guarda y reutiliza listas de alumnos
- Todo persiste en localStorage entre sesiones

### 6 idiomas
Castellano, Catala, Euskara, Galego, Valencia, English — cambio instantaneo

### +45 iconos
Iconos SVG tematicos con buscador multilingue para personalizar cada rubrica

---

## Stack

- **HTML + CSS + JS vanilla** en un unico archivo
- **localStorage** para persistencia
- **Zero dependencias** (solo Google Fonts para tipografia)
- Funciona con abrir el archivo en el navegador

---

## Licencia

MIT
