
# Las aplicaciones de la IA

Basada en el modelo **Codex** de OpenAI, esta herramienta utiliza machine learning para generar sugerencias de código, siendo algunas de las aplicaciones claves de esta IA son:

## Generación de código automatizada
**GitHub Copilot**, puede escribir automáticamente fragmentos completos de código, lo que facilita la tarea del desarrollador. Esta generación automática no se limita a simples líneas de código, sino que abarca funciones enteras, clases y estructuras más complejas. Junto a esto es capaz de identeficar inconsistencias o malas practicas por parte del usuario, algunos detalles de este apartado son:

- **Contextualización:** Utiliza el contexto del código que ya has escrito para generar automáticamente líneas que son relevantes para el fragmento en cuestión. Si, por ejemplo, estás escribiendo una función en Python para conectar a una base de datos, Copilot puede completar el código utilizando las bibliotecas y métodos más adecuados, como sugerancias. Copilot no puede ejecutar comandos en tu entorno, por razones de segurirdad del entorno del ususario.
- **Flexibilidad:** El usuario puede aceptar, modificar o rechazar las sugerencias, lo que otorga un gran control sobre el proceso. Si una sugerencia no es útil, se puede descartar rápidamente, pero la posibilidad de tener algo preconfigurado siempre acelera la productividad.

## Educacion y formación
Copilot también actúa como una herramienta educativa, especialmente valiosa para nuevos desarrolladores o para quienes están aprendiendo nuevos lenguajes y tecnologías.

- Los desarrolladores pueden aprender nuevas sintaxis, librerías y patrones de programación simplemente observando las sugerencias de Copilot.
- Copilot puede generar explicaciones, comentarios y ejemplos que aclaran el funcionamiento del código.

**Ejemplo:** Un estudiante que no está familiarizado con SQL podría escribir:

    -- Crear una tabla para almacenar información de usuarios.

A lo cual, la IA generará:

    CREATE TABLE usuarios (
        id SERIAL PRIMARY KEY,
        nombre VARCHAR(100),
        correo VARCHAR(100) UNIQUE,
        fecha_registro TIMESTAMP DEFAULT CURRENT_TIMESTAMP
    );

De esta forma, los desarrolladores pueden aprender en el contexto de su trabajo, asi como, se les facilita la transición a nuevos frameworks o lenguajes.

## Refactorizacion de código
La refactorización es el proceso de reescribir y reorganizar el código existente para mejorar su legibilidad, eficiencia y mantenibilidad, sin alterar su funcionalidad. Este proceso es clave para mantener un software robusto y escalable, especialmente en proyectos a largo plazo.

<div align="center">
  <img src="/Imagenes/copilot-chat-fix-error-code.png" alt="Copilot Interface">
</div>

- La herramienta analiza patrones comunes en tu código y propone formas más eficientes de escribirlos. Esto es útil para eliminar redundancias, mejorar la claridad y minimizar errores.
- Copilot sugiere actualizar el código para adoptar estándares actuales, como el uso de nuevas características del lenguaje o librerías optimizadas.
- Cuando estás implementando algoritmos, Copilot puede sugerir mejores enfoques con base en conocimientos avanzados.

---

### Limitaciones y consideraciones

1. **Comprensión del contexto:** Copilot no siempre entiende el propósito completo de tu código, por lo que sus sugerencias pueden no ajustarse a casos específicos.
2. **Validación humana necesaria:** Aunque las sugerencias sean útiles, es fundamental revisar y validar las propuestas antes de implementarlas.
3. **Foco en tareas locales:** Copilot se centra en mejorar fragmentos específicos; las optimizaciones globales requieren intervención manual.

---

[Anterior](Desenvolupament5.md) | [1](Desenvolupament5.md) | [2](Las_aplicaciones_de_la_IA5.md) | [3](inpacto_en_el_sector5.md) | [4](Impacto_ambiental5.md) | [5](Propostes_per_minimitzar_els_impactes_ambientals5.md) | [Siguiente](inpacto_en_el_sector5.md)

