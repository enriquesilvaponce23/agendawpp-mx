# Agendawpp MX Landing

## Producto

Agendawpp es un sistema de agendamiento de citas por **WhatsApp Flows™** (formularios nativos oficiales de Meta). **NO es un chatbot, NO es IA, NO es un bot conversacional.** Los clientes reservan citas desde un formulario visual dentro de WhatsApp con dropdowns (servicio, profesional, fecha, hora), sincronizado en tiempo real con Google Calendar.

Diferenciadores clave:
- WhatsApp Flows (formularios oficiales de Meta), no conversación con bot
- Sync bidireccional en tiempo real con Google Calendar
- Recordatorios automáticos 24h y 2h antes con botones interactivos (Confirmar/Reagendar/Cancelar)
- Usa números verificados dedicados de WhatsApp Business API (no el número personal del usuario)
- Dashboard para configurar servicios, horarios, duraciones, logo y marca
- Más rápido que cualquier chatbot: el cliente selecciona en lugar de escribir

## Mercado objetivo

Mexico. Subdominio: agendawpp.mx. Cualquier profesional que venda su tiempo (doctores, dentistas, barberos, salones, nutriólogos, psicólogos, veterinarias, spas, consultores, etc.)

## Estructura del proyecto

```
index.html                  — Landing page principal (Agendawpp MX)
landing-agentes-ia.html     — Landing alternativa para producto de Agentes IA (guardada para futuro uso)
logo.png                    — Logo del producto
favicon.png                 — Favicon
apple-touch-icon.png        — Icono para iOS
.agents/skills/             — 34 marketing skills instaladas
.claude/skills/             — Symlinks a .agents/skills/
```

Proyecto estático: un solo archivo HTML con CSS y JS inline. Sin framework, sin build tools.

## Demo

- Número MX: +52 1 614 599 3425
- Código de demo: AGENDAWPP
- Link: `https://wa.me/5216145993425?text=AGENDAWPP`

## Decisiones de diseño

- **Tema oscuro** con acentos verdes (#25D366) — diferenciado de agendawpp.com
- **CTA único**: llevar tráfico a WhatsApp para probar el demo. Sin trial, sin precios, sin registro
- **Mockups CSS**: los 3 pasos (Enlace Inteligente, Menú Rápido, Reserva Visual) están hechos con HTML/CSS, no imágenes
- **Floating CTA**: botón fijo en móvil que aparece al hacer scroll pasado el hero

## Reglas de copy

- Siempre referirse al producto como "WhatsApp Flows" o "formularios dentro de WhatsApp"
- Nunca usar "bot", "chatbot", "IA", "inteligencia artificial" para describir Agendawpp
- Español mexicano natural, sin jerga técnica innecesaria
- Copy orientado a beneficios y resultados, no features técnicas

## Producto relacionado

La página de referencia principal es https://agendawpp.com — contiene la descripción completa del producto, pricing ($24.99 USD/mes), FAQ, y toda la documentación comercial.
