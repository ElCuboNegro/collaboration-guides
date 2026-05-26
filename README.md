# Guía de Colaboración para los Tiempos de la IA

Somos un equipo que trabaja con herramientas de IA disponibles las 24 horas. Eso cambia la economía de las interrupciones, la responsabilidad sobre el conocimiento y la forma en que nos comunicamos. Esta guía es una adaptación de los [principios de colaboración de Buritica](https://github.com/buritica/collaboration-guides) para un contexto donde la IA ya es un compañero de equipo más.

---

## Antes de interrumpir a alguien

El tiempo de tus compañeros sigue siendo el recurso más escaso. Antes de buscar a alguien, recorre esta escalada:

1. **Pregunta a una IA.** Claude, Copilot, Gemini — lo que tengas disponible. Invierte al menos 2 minutos. Si la respuesta requiere contexto que solo vive en tu cabeza, dáselo explícitamente.
2. **Busca en las fuentes autorizadas.** Documentación del proyecto, issues, historial de decisiones (ADRs), wikis. Si la respuesta debería estar ahí y no está, créala después de encontrarla.
3. **Evalúa si la información es sensible.** Credenciales, datos personales, información financiera, configuraciones de producción — no las pongas en el chat de IA ni en mensajes no cifrados. Usa los canales seguros del equipo.
4. **Evalúa si es urgente.** Urgente significa que algo se detiene en los próximos diez minutos. Si puede esperar una hora, no es urgente.
5. Solo entonces, busca a un compañero.

---

## Jerarquía de comunicación (de menos a más intrusivo)

| Canal | Cuándo usarlo | Tiempo esperado de respuesta |
|---|---|---|
| Herramienta de IA | Siempre como primer intento | Inmediato |
| Microsoft Teams | Decisiones, solicitudes y conversaciones que requieren trazabilidad o historial auditable | 24 h |
| Grupo de WhatsApp | Avisos no urgentes, ACKs generales, información de baja prioridad para todo el equipo | 4–12 h |
| Mensaje directo (WhatsApp o Teams) | Asuntos personales o moderadamente urgentes | 2–4 h |
| Llamada | Únicamente si algo está caído o bloqueado en este momento | Inmediato |

La IA no reemplaza el juicio humano; reduce el ruido para que cuando preguntes a una persona, la pregunta valga la pena.

---

## Etiqueta con herramientas de IA

### Antes de enviar algo generado por IA

- **Léelo.** Tú eres responsable del contenido que firmas o envías, no el modelo.
- **Verifica los datos.** Los modelos confabulan fechas, cifras y referencias. Comprueba lo que importa.
- **Adáptalo al contexto.** Un borrador es un borrador. Editarlo es parte del trabajo.

### Al compartir outputs de IA con el equipo

- Si un documento fue generado o revisado significativamente por IA, dilo. No por protocolo burocrático, sino para que quien lo revise calibre su nivel de escrutinio.
- No compartas prompts que incluyan datos sensibles del negocio fuera de los entornos aprobados.
- Si encontraste un prompt que funciona muy bien para una tarea recurrente del equipo, compártelo en la base de conocimiento compartida — eso multiplica el valor para todos.

---

## El contexto es el nuevo código fuente

Una IA sin contexto adecuado da respuestas genéricas. El contexto que construyes y documentas es lo que diferencia un asistente mediocremente útil de uno que realmente acelera tu trabajo.

### Qué significa esto en la práctica

- **Mantén la documentación actualizada y legible.** README, ADRs, CLAUDE.md, runbooks — si un modelo puede leerlos y entenderlos, también lo puede un compañero nuevo. Mata dos pájaros.
- **Escribe decisiones, no solo resultados.** "Elegimos Postgres porque…" es más valioso que "usamos Postgres". El *por qué* es lo que ni el código ni la IA pueden inferir solos.
- **Si tuviste que explicarle algo a una IA tres veces, es señal de que eso debería estar documentado.**

---

## Qué NO delegar a la IA

La IA es excelente para síntesis, exploración, borradores, traducción y resúmenes. Es mala consejera para:

- **Decisiones que afectan a personas.** Evaluaciones de desempeño, conflictos de equipo, despidos, ascensos. Estas requieren juicio humano y rendición de cuentas humana.
- **Información confidencial o PII.** Datos personales de clientes o empleados, información financiera no pública, configuraciones de producción con credenciales. No los pongas en ningún modelo externo.
- **Situaciones donde el error tiene alto costo o es irreversible.** La IA sugiere; tú decides. Si la consecuencia de equivocarse es seria, el humano tiene que entender la lógica, no solo aprobar la salida.
- **Conflictos interpersonales.** Una conversación difícil necesita empatía, no eficiencia. La IA puede ayudarte a prepararte para ella, no a sustituirla.

---

## Trabajo profundo y disponibilidad

El hecho de que la IA esté disponible 24/7 no significa que tú debas estarlo.

- Protege bloques de trabajo profundo. Comunica al equipo cuándo estás en ese modo y cuándo no.
- Usa la IA para responder preguntas frecuentes asíncronamente — una nota bien escrita con el contexto correcto puede reemplazar una reunión.
- Si estarás fuera de disponibilidad por más de una hora en horario de trabajo, avisa con anticipación y asegura cobertura.

---

## Cuando alguien te pide ayuda

- **Responde con paciencia.** Asume que ya intentaron con IA y con búsqueda antes de llegar a ti.
- **Si no puedes atenderlo en este momento, dilo.** "No puedo ahora, ¿en dos horas está bien?" es una respuesta válida y respetuosa.
- **Si sabes dónde está la información, comparte el enlace** — y si no existe ese enlace, crea la documentación después de resolver.
- **Mueve la conversación a un foro público** cuando la respuesta beneficia a más de una persona. El conocimiento que vive solo en mensajes directos muere con el hilo.

---

## Discusiones y desacuerdos

- Si el desacuerdo es sobre un hecho verificable, busca juntos la fuente — o pídanle a una IA que cite su razonamiento para poder auditarlo.
- Si el desacuerdo es sobre una decisión de diseño o estrategia, abre un issue o un ADR con los argumentos escritos. Escribir fuerza claridad.
- Si hay tensión emocional, sal del canal escrito. Un mensaje de texto nunca transmite el tono que imaginas. Una llamada de diez minutos resuelve lo que veinte mensajes empeoran.
- Nunca uses lenguaje pasivo-agresivo. "Como ya dijimos…" no ayuda a nadie.

---

## Si alguien no sigue estas pautas

- Asume que no fue intencional.
- La primera vez, señálalo en privado y comparte este documento.
- Si persiste, escala con contexto a quien corresponda.

---

## Nota final

La IA no nos hace más listos ni más rápidos por sí sola — lo que nos hace mejores es usarla para eliminar el ruido que no debería llegar a las personas, y dejar que las personas se concentren en lo que solo las personas pueden hacer: juzgar, crear, conectar y responsabilizarse.

Este documento es un punto de partida, no un reglamento. Si algo no funciona o falta algo relevante para tu equipo, abre una discusión y modifícalo. La guía que nadie actualiza es la guía que nadie lee.

---

*Adaptado del trabajo original de [Juan Pablo Buritica](https://github.com/buritica/collaboration-guides). Licencia original mantenida.*
