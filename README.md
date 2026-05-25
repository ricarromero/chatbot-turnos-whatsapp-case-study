# Sistema de Gestión de Turnos con Chatbot de WhatsApp

Sistema web para la gestión de turnos de un estudio jurídico especializado en Derecho de Familia.

El proyecto incluye un chatbot de WhatsApp, un panel administrativo privado, calendario de turnos, gestión de disponibilidad y simulador de conversación.

> Este repositorio funciona como presentación pública del proyecto.  
> El código fuente completo se mantiene en un repositorio privado por motivos de seguridad, configuración interna y protección del desarrollo.

## 📌 Problema

Un estudio jurídico puede recibir consultas y solicitudes de turno en distintos horarios, incluso fuera del horario laboral.

Gestionar manualmente los turnos puede generar demoras, errores, superposición de horarios o pérdida de oportunidades de contacto.

## 💡 Solución

El sistema permite automatizar la solicitud de turnos mediante un chatbot de WhatsApp disponible 24/7.

El bot guía al cliente paso a paso, solicita datos básicos y ofrece horarios disponibles sin brindar asesoramiento legal.

Desde el panel administrativo, el estudio puede consultar, editar y administrar los turnos agendados.

## 🚀 Funcionalidades principales

- Chatbot de WhatsApp para solicitud de turnos
- Flujo conversacional rígido mediante máquina de estados
- Panel administrativo privado
- Login seguro
- Dashboard con turnos del día
- Tabla de citas con filtros y buscador
- Calendario mensual propio
- Gestión visual de disponibilidad
- Bloqueo de horarios y feriados
- Simulador de WhatsApp integrado
- Prevención de doble reserva
- Persistencia local para pruebas
- Integración opcional con Supabase
- Webhook preparado para WhatsApp Cloud API

## 🛠️ Stack tecnológico

- Next.js
- React
- TypeScript
- Tailwind CSS
- API Routes de Next.js
- Supabase
- WhatsApp Cloud API
- JWT
- Middleware de Next.js

## 🧱 Arquitectura general

El sistema está dividido en tres partes principales:

- Landing pública del estudio
- Panel administrativo privado
- Motor conversacional del chatbot

El bot funciona mediante una máquina de estados para controlar el flujo y evitar respuestas libres o asesoramiento legal automático.

## 💬 Flujo básico del chatbot

1. El cliente inicia la conversación.
2. El bot solicita nombre completo.
3. El bot solicita ciudad y provincia.
4. El sistema muestra horarios disponibles.
5. El cliente selecciona una opción.
6. El turno queda registrado en el panel.

## 📸 Capturas

Próximamente se agregarán capturas del sistema.

## 📚 Aprendizajes

Durante el desarrollo de este proyecto trabajé en:

- Automatización de turnos
- Diseño de flujos conversacionales
- Manejo de estados
- Prevención de doble reserva
- Paneles administrativos
- Integración con APIs externas
- Separación entre lógica del bot y gestión interna

## 🔒 Estado del código

El código fuente completo se mantiene en un repositorio privado.

Este repositorio público tiene como objetivo presentar el proyecto, su arquitectura, funcionalidades y alcance técnico.

## 🔮 Mejoras futuras

- Integración completa con WhatsApp Business en producción
- Notificaciones automáticas de recordatorio
- Confirmación y cancelación de turnos desde WhatsApp
- Integración con Google Calendar
- Panel de estadísticas de atención
