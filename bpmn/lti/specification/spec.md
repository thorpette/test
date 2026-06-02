# Specification

Version 1 | 2026-06-02T09:06:42.143663+00:00 | Generado por IA (deepseek-pro) — 10 requirements

By: oscar.hidalgo.puertas@gmail.com

**Title:** Requirements iniciales (IA)
**Mode:** requirements_only

## Requirements (10)

### 1. Autenticación segura con control de acceso basado en roles
Sistema de inicio de sesión seguro para reclutadores y hiring managers. Gestiona permisos según perfil y ofrece autenticación de doble factor como opción.

### 2. Carga de CVs en PDF con procesamiento masivo e individual
Interfaz para subir archivos PDF mediante drag & drop o selección, con verificación de formato, barra de progreso y asociación a una vacante existente.

### 3. Validación automática y extracción inteligente de CV con IA
Procesamiento asíncrono que analiza cada CV: verifica legibilidad, extrae datos estructurados (nombre, experiencia, habilidades, formación) y marca aquellos que no cumplen requisitos mínimos.

### 4. Sistema de notificaciones al hiring manager
Alertas configurables que, tras la validación y revisión del CV por el reclutador, envían un resumen del candidato al responsable de contratación por correo electrónico, push o integración con herramientas de mensajería.

### 5. Revisión y edición de datos extraídos del CV
Ficha del candidato donde el reclutador visualiza los campos extraídos por IA, corrige imprecisiones y añade notas internas antes de compartir la información con el hiring manager.

### 6. Perfil del candidato y gestión del onboarding
Perfil completo con datos extraídos, estado del proceso, documentos adicionales y checklist de tareas de bienvenida. El hiring manager puede seguir el avance y solicitar más información.

### 7. Búsqueda y filtrado avanzado de candidatos
Motor de búsqueda para localizar candidatos por palabras clave, habilidades, fecha de carga, estado del proceso o reclutador asignado, con filtros predefinidos y resultados ordenables.

### 8. Configuración administrativa de la cuenta
Panel para que administradores personalicen flujos de validación, plantillas de notificación, criterios de extracción de la IA y políticas de RGPD. No accesible para otros roles.

### 9. Cumplimiento del RGPD y gestión de consentimientos
El sistema debe garantizar el tratamiento legal de datos personales, incluyendo registro de consentimiento, base jurídica, políticas de retención, derecho al olvido y portabilidad de datos.

### 10. Rendimiento y escalabilidad del sistema
La plataforma debe manejar cargas de trabajo concurrentes, especialmente en momentos de alta subida de CVs, sin degradación significativa y con capacidad de crecer horizontalmente.
