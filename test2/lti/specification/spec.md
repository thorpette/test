# Specification

Version 1 | 2026-06-02T13:06:45.379567+00:00 | Generado por IA (mimo) — 11 requirements

By: oscar.hidalgo.puertas@gmail.com

**Title:** Requirements iniciales (IA)
**Mode:** requirements_only

## Requirements (11)

### 1. Subida de CVs mediante drag & drop
Módulo que permite a los reclutadores arrastrar uno o varios archivos PDF para su carga. El sistema realiza validación inmediata del formato, tamaño y ausencia de malware antes de aceptar el archivo.

### 2. Procesamiento inteligente de CVs con IA
Motor de IA que extrae datos estructurados del CV: datos personales, experiencia, formación, habilidades, idiomas y certificaciones. Presenta un nivel de confianza por campo y permite corrección manual de campos con baja confianza.

### 3. Ficha editable del candidato
Pantalla donde el reclutador revisa y completa la información extraída por la IA. Permite añadir notas internas, etiquetas personalizadas y adjuntar el CV original. Incluye botón de aprobación que dispara la notificación al hiring manager.

### 4. Gestión de consentimiento RGPD
Consola que obliga al reclutador a confirmar consentimiento explícito del candidato antes de procesar su CV. Registra trazas de consentimiento y permite configurar políticas de retención y anonimización automática.

### 5. Notificaciones automáticas al hiring manager
Sistema de notificaciones que alerta al hiring manager asignado cuando un perfil de candidato es aprobado. Incluye resumen del candidato, coincidencia con el puesto y enlace directo al perfil completo.

### 6. Pipeline Kanban de candidatos
Tablero visual tipo Kanban donde el equipo de selección arrastra candidatos entre etapas: Nuevo, Revisión, Entrevista, Oferta, Contratado/Descartado. Permite añadir recordatorios y registrar actividades por candidato.

### 7. Dashboard con indicadores clave del proceso
Panel de control que muestra KPIs en tiempo real: CVs subidos hoy, pendientes de validación, extracciones completadas, candidatos notificados y tiempo medio de procesamiento. Incluye accesos rápidos a las funciones principales.

### 8. Portal de autoservicio para derechos ARCO del candidato
Portal web público donde los candidatos pueden ejercer sus derechos de acceso, rectificación, cancelación y oposición sobre sus datos. Solicita verificación de identidad y procesa las peticiones según la política de retención configurada.

### 9. Integración con ATS externos y calendarios
Conectores que permiten sincronizar candidatos y estados del pipeline con sistemas ATS de terceros y calendarios corporativos. Configurable desde el panel de administración con claves API y mapeo de campos.

### 10. Autenticación multifactor y control de acceso por roles
Implementación de verificación en dos pasos obligatoria para todos los usuarios. Control de acceso basado en roles (RBAC) que restringe funcionalidades según perfil: Reclutador, Hiring Manager, Administrador.

### 11. Rendimiento del procesamiento de CVs con IA
Requisitos de rendimiento para el motor de extracción de IA y la plataforma general. El sistema debe soportar carga concurrente de múltiples reclutadores procesando lotes de CVs simultáneamente sin degradación perceptible.
