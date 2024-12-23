# Toma de Requisitos para el Bot de Telegram

## 1. Objetivo del Bot
Facilitar la conexión entre reclutadores y postulantes a través de telegram.

## 2. Requisitos Funcionales

### 2.1. Registro de Usuarios
- Postulantes:
  - Crear un perfil con:
    - Nombre completo
    - Correo electrónico
    - Número de teléfono
    - Experiencia laboral
    - Habilidades
    - Ubicación
  - Opción para subir un CV.
  
- Reclutadores:
  - Crear un perfil con:
    - Nombre de la empresa
    - Nombre del reclutador
    - Correo electrónico
    - Número de teléfono
    - Descripción de la empresa

### 2.2. Filtrado y Coincidencias
- Sistema que permita a los reclutadores buscar candidatos basados en:
  - Ubicación geográfica
  - Habilidades específicas
  - Experiencia laboral
- Notificaciones automáticas a reclutadores cuando se registren nuevos postulantes que cumplan con sus criterios.

### 2.3. Entrevistas Automatizadas
- Funcionalidad para enviar preguntas predefinidas a los postulantes.
- Opción para que los postulantes respondan directamente en el chat.

### 2.4. Notificaciones de Oportunidades
- Alertas automáticas a los postulantes sobre nuevas vacantes que coincidan con su perfil.
- Posibilidad de personalizar las notificaciones según preferencias del usuario.

### 2.5. Feedback y Seguimiento
- Permitir a los reclutadores enviar retroalimentación a los postulantes sobre su aplicación.
- Funcionalidad para que los postulantes consulten el estado de sus aplicaciones.

## 3. Requisitos No Funcionales
- Usabilidad: Interfaz amigable y fácil de usar.
- Seguridad: Protección de datos personales y cumplimiento con normativas de privacidad.
- Escalabilidad: Capacidad para manejar un número creciente de usuarios sin afectar el rendimiento.
- Disponibilidad: El bot debe estar disponible 24/7 para consultas y aplicaciones.

## 4. Tecnologías Sugeridas
- Lenguaje de programación: Python (usando python-telegram-bot).
- Base de datos: PostgreSQL o MongoDB para almacenar perfiles y datos.
- Hosting: Heroku, AWS o cualquier otro servicio que soporte bots de Telegram.

## 5. Plan de Desarrollo
1. Definición del alcance y diseño del flujo del bot.
2. Desarrollo del backend (API, base de datos).
3. Implementación del bot en Telegram.
4. Pruebas con usuarios reales para obtener feedback.
5. Lanzamiento y promoción del bot.