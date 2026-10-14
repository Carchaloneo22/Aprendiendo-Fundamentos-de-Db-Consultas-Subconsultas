
# BD·111 · Subconsultas en SQL Server

¡Bienvenido al repositorio del tutorial **BD·111 sobre Subconsultas** en SQL Server! Este material forma parte de la Fase 4 (Consultar Avanzado) del programa de formación de bases de datos. Está diseñado bajo un enfoque práctico, visual y estructurado para aprender a realizar consultas dentro de otras consultas.

---

## 📂 Contenido del Tutorial

El material está dividido en 8 unidades principales, una chuleta de referencia rápida y un glosario completo:

1. **¿Qué es una subconsulta?** *(Unidad 01)*
   - Introducción conceptual: el problema de calcular un promedio dinámico.
   - La regla de oro y los cuatro lugares donde se puede ubicar una subconsulta (`WHERE`, `FROM`, `SELECT`, `HAVING`).

2. **Subconsultas escalares** *(Unidad 02)*
   - Operadores de comparación estándar (`=`, `>`, `<`, `>=`, `<=`, `<>`).
   - Ejemplos prácticos utilizando la base de datos de la Veterinaria Huellitas.

3. **IN, ANY y ALL** *(Unidad 03)*
   - Manejo de subconsultas que devuelven listas de valores.
   - Diferencias entre `IN`, `NOT IN`, `ANY` y `ALL`.
   - Precauciones críticas con valores `NULOS` (`NULL`) al usar `NOT IN`.

4. **Tablas derivadas en el FROM** *(Unidad 04)*
   - Uso de subconsultas como tablas virtuales temporales.
   - Requerimiento de alias y combinación (`JOIN`) con tablas reales.

5. **EXISTS y NOT EXISTS** *(Unidad 05)*
   - Verificación lógica de existencia de filas (verdadero / falso).
   - Comparación de rendimiento y legibilidad frente a `IN` y `JOIN`.

6. **Subconsultas correlacionadas** *(Unidad 06)*
   - Consultas que dependen de cada fila exterior.
   - Patrones avanzados como el valor máximo o conteo por grupo (`GROUP BY` implícito por fila).

7. **Subconsultas en el SELECT y VS JOIN** *(Unidad 07)*
   - Inserción de subconsultas escalares en la lista de columnas.
   - Comparación directa entre el uso de `JOIN` y subconsultas: ¿cuándo elegir cada una?

8. **Taller Práctico de 32 Ejercicios** *(Unidad 08)*
   - 6 bloques organizados por tipo de subconsulta y dificultad (Fácil, Medio, Difícil).
   - Incluye código desplegable con soluciones comentadas y autoevaluación final.

---

## 🛠️ Requisitos e Instalación

- **Motor de Base de Datos:** Microsoft SQL Server (compatible con SQL Server Management Studio - SSMS).
- **Esquema Base:** Las consultas y ejemplos están adaptados sobre el modelo relacional de la **Veterinaria Huellitas** (visto en entregas previas como `BD·109`).
- **Visualización del Tutorial:** El archivo principal `.html` es autocontenido (incluye estilos CSS modernos y diseño responsivo). No requiere instalación de dependencias ni conexión a internet para su lectura (usa fuentes locales/Google Fonts si hay conectividad).

---

## 🚀 Uso Rápido

1. Abre el archivo HTML del tutorial en cualquier navegador web moderno (Chrome, Firefox, Edge, Safari).
2. Utiliza la barra de navegación superior fija para saltar directamente entre las unidades teóricas y los ejercicios.
3. Si deseas practicar, abre SSMS y ejecuta los ejemplos de código copiando las consultas de los bloques oscuros.
4. Para imprimir o guardar como PDF en tus apuntes, presiona `Ctrl + P` (o `Cmd + P` en Mac).

---

## 📜 Licencia
Versión 1.0 (2026). Permitida su reproducción con fines educativos citando la fuente original.
