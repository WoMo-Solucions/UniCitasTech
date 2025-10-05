# 🎓 UniCitasTech  
## Sistema Integral de Gestión de Tutorías Universitarias  

![Estado](https://img.shields.io/badge/🚀_En_Desarrollo-blue) ![Licencia](https://img.shields.io/badge/Licencia-🔒_Privada-red) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![n8n](https://img.shields.io/badge/n8n-Automation-orange?logo=n8n&logoColor=white)  ![Supabase](https://img.shields.io/badge/Supabase-Auth_%26_DB-3ECF8E?logo=supabase&logoColor=white) 

## 📋 Descripción del Sistema  
Es una solución tecnológica enfocada en la **gestión inteligente y automatizada de tutorías universitarias**.  
Su objetivo es eliminar la gestión manual de citas, centralizando el flujo entre **estudiantes y tutores** mediante reservas digitales con notificación automática y control de disponibilidad en tiempo real.  

Incluye:  
- Registro y autenticación segura de usuarios (Supabase Auth)  
- Administración de tutores, materias y carreras  
- Bloqueo automático de horarios reservados  
- Notificación por correo corporativo (n8n + Gmail)  
- Interfaz responsive accesible desde cualquier dispositivo  

## 🛠 Stack Tecnológico  
**Backend Automatizado:**  
- n8n (Render) – Webhooks para disponibilidad y reservas  
- Supabase (PostgreSQL) – Persistencia de datos y autenticación  
- Gmail corporativo – SMTP seguro para notificaciones  
- RLS (Row Level Security) – Políticas de acceso controlado  

**Frontend:**  
- HTML5 + CSS3 + JavaScript (Vanilla)  
- Diseño responsive adaptable (Android / iOS / Escritorio)  
- Integración directa con Supabase Auth  

## 🖥️ Infraestructura  
**Entorno de Desarrollo / MVP:**  
- Frontend estático (Render o GitHub Pages)  
- Backend automatizado (n8n en Render)  
- Base de datos administrada (Supabase PostgreSQL)  
- Cifrado de contraseñas gestionado por Supabase  
- Envío de correos corporativos mediante SMTP  

## 🚀 Próximas Implementaciones  
- Panel administrativo para bienestar universitario  
- Historial de tutorías por estudiante  
- Reportes estadísticos de asignaturas más solicitadas  
- Integración con calendarios institucionales  

## 🖥️ Estructura del Proyecto  
📁 UniCitasTech  
├── 📂 data/ # Configuración base (catálogo inicial)  
├── 📂 static/  
│ ├── 📂 css/ # Estilos visuales  
│ ├── 📂 js/ # Lógica de autenticación y reservas  
│ └── 📂 img/ # Logo e imagotipo WoMo Soluciónˢ  
├── 📄 index.html # Login / Registro  
├── 📄 dashboard.html # Agenda y reservas  
└── 📂 docs/ # Documentación y esquema SQL  

## 🔍 Características Clave  
- Sistema de autenticación con Supabase (hash + JWT)  
- Reservas únicas por tutor, fecha y hora  
- API REST con n8n para disponibilidad y reservas  
- Correos automáticos a tutores al confirmar citas  
- Panel responsive para gestión desde cualquier dispositivo  

## 🛡️ Seguridad Avanzada  
- Contraseñas cifradas (bcrypt – Supabase Auth)  
- Políticas RLS activas en todas las tablas críticas  
- Uso restringido de Service Role Key (solo en n8n)  
- Prevención de reservas duplicadas  
- Sesión activa validada antes de acceso al panel  

## 📊 Métricas de Rendimiento  
- Latencia promedio: <250ms  
- Disponibilidad esperada: 99.9%  
- Escalabilidad vertical inmediata (Supabase clusters)  
- Capacidad estimada: 500 usuarios concurrentes  

## 📝 Gestión de Versiones  
- Estructura GitFlow  
- Despliegue modular (frontend / backend / db)  
- Versionado semántico  
- Integración con Render CI/CD  

## 📬 Contacto Corporativo  
**Julián Alberto Ramírez**  
💻 Socio Fundador & Visionario Tecnológico  
⚙️ Automatización | 🧩 Soluciones software | 💡 Innovador Tecnológico | 🔍 Apasionado por IA  
<img width="222" height="29" alt="Logo WSˢ" src="https://github.com/user-attachments/assets/24519130-f605-4762-a4f2-374c450f2b64" />  
🏢 **Soluciones Tecnológicas Avanzadas – WoMo Soluciónˢ**  
<img width="150" height="150" alt="Logo" src="https://github.com/user-attachments/assets/09c23a95-e483-452e-880f-e7c90c222014" />  

💡 **Notas Técnicas:**  
Este sistema está diseñado para:  
✅ Automatizar la gestión de tutorías universitarias  
✅ Centralizar la comunicación entre estudiantes y tutores  
✅ Garantizar integridad de datos y seguridad autenticada  

"Educación conectada, sin papeleo y sin esperas."  

📅 **Control de Versiones**  

![Versión](https://img.shields.io/badge/Versión-1.0.0-blue) ![Última Actualización](https://img.shields.io/badge/Actualizado-Oct_2025-green)
