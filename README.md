# Tu IA — Asistente Personal Premium

Asistente de IA elegante con personalidad camaleón adaptable, memoria personal profunda, y soporte para Claude (Anthropic) y GPT (OpenAI).

## Funcionalidades

- 💬 Chat con dos cerebros: Claude 4.6 y GPT-4o
- 🧠 Memoria personal profunda (aprende cosas tuyas con el tiempo)
- 📅 Conoce la fecha y hora actual
- 📂 Conversaciones guardadas con sidebar tipo ChatGPT
- 📋 Copiar y regenerar respuestas
- 📥 Exportar conversaciones como Markdown
- ⌨️ Atajos de teclado profesionales
- 🎨 Diseño elegante premium oscuro con dorado champagne
- 📱 Responsive (funciona en móvil)

## Cómo usar

1. Abre el sitio
2. La primera vez te pedirá tu llave API de Anthropic (Claude) y/o OpenAI (GPT)
3. Empieza a hablar

Las llaves se guardan solo en tu navegador (localStorage). Nunca se envían a otro servidor.

## Privacidad

- Tus llaves API se guardan únicamente en tu navegador
- Tus conversaciones y memorias se guardan únicamente en tu navegador
- Nada se sube a ningún servidor de terceros
- Las llaves solo se usan para llamar a Anthropic / OpenAI directamente

## Stack técnico

- HTML, CSS, JavaScript vanilla (sin frameworks)
- marked.js para renderizado markdown
- Streaming de respuestas (SSE)
- Hosted en Vercel
