# Chatbot para Gimnasio – Automatización de Flujos

Este proyecto consiste en un chatbot diseñado para automatizar respuestas y guiar al usuario en la elección de clases, planes y horarios dentro de un gimnasio. Utiliza lógica condicional y estructuras de decisión (tipo árbol) que se planificaron en diagramas realizados con Draw\.io.

##  Funcionalidades principales

- Mostrar horarios y clases disponibles.
- Ofrecer información sobre planes.
- Validar respuestas del usuario (inputs como horarios o días correctos).
- Redireccionar al menú principal según la acción elegida.
- Permitir contacto vía WhatsApp al finalizar ciertas acciones.

##  Lógica implementada

- Flujos de conversación con nodos de decisión (sí/no, elegir día, elegir hora, etc.).
- Validación de errores básicos (por ejemplo: si el usuario escribe un día incorrecto, se lo vuelve a preguntar).
- Separación clara de secciones: clases, horarios, planes, contacto, etc.

## Herramientas utilizadas

- 🧩 **Draw\.io** para el diseño de los diagramas de flujo (flujo conversacional del chatbot).
- 📄 **Markdown** para documentar el proyecto.

## 📚 Documentación del flujo conversacional

### Ejemplo de agendamiento de clase:

```
Usuario: Quiero agendar Cross
Bot: ¿Qué día querés venir? Lunes a Viernes
Usuario: Martes
Bot: Horarios disponibles el martes: 07:00, 08:00, 09:00, ..., 19:30
Usuario: 17:00
Bot: ¡Listo! Clase Cross agendada para el martes a las 17:00 💪
```

Incluye validación de día y horario (con mensaje de error si se ingresa algo inválido).

### Ejemplo de consulta de planes:

```
Bot: Nuestros planes actuales:
- Libre mensual: $35.000
- 3 veces por semana: $20.000
- Trimestral: $55.000
¿Querés que alguien te contacte por WhatsApp?
(Sí / No)
```

Si el usuario responde “sí”, se le solicita nombre y número.


##  Link para ver el diagrama en draw.io:
[🔍 Abrir diagrama en Draw.io](https://app.diagrams.net/?url=https://raw.githubusercontent.com/ivanveliz/chatbot/main/chatBotH%C3%A9roes.drawio#G14uuM-L_FAdpZzBkI5gG4MK1swFdh6NU7#%7B%22pageId%22%3A%22C5RBs43oDa-KdzZeNtuy%22%7D)

##  Archivos incluidos
- `chatBotGimnasio.jpg` → Diagrama general del flujo del chatbot.
- `/readme.md` → Documentación del proyecto.
-`chatBotHéroes.jpg` → Imagen del chat en png.


##  Licencia

Este proyecto fue realizado con fines de práctica y aprendizaje.

---

 Si querés aportar, proponer mejoras o tenés dudas, ¡escribime!

Realizado por Iván Veliz

