# 🎓 UniCitasTech  
## Sistema Integral de Gestión de Tutorías Universitarias  

![Estado](https://img.shields.io/badge/🚀_En_Desarrollo-blue) ![Licencia](https://img.shields.io/badge/Licencia-🔒_Privada-red) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-Auth_%26_DB-3ECF8E?logo=supabase&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![n8n](https://img.shields.io/badge/n8n-Automation-orange?logo=n8n&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-Containerization-2496ED?logo=docker&logoColor=white) ![Render](https://img.shields.io/badge/Render-Cloud_Deploy-0099FF?logo=render&logoColor=white)

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
**Backend:**
- Flask (Python 3.10+) o Node.js/Express según proyecto
- Autenticación JWT / RBAC

**Base de Datos:**
- PostgreSQL en **Supabase** (Auth + RLS + REST)

**Frontend:**
- HTML5, CSS3 (Bootstrap 5), JavaScript (ES6+)
- Chart.js / componentes UI según proyecto

**Automatizaciones:**
- **n8n** para reportes, alertas, integraciones y jobs programados


## 🖥️ Infraestructura
**Render (Producción):**
- Servicios separados: `frontend`, `backend`, `n8n` (todos en **Docker**)
- HTTPS forzado, variables de entorno seguras

**Supabase:**
- PostgreSQL gestionado, políticas **RLS**, autenticación y almacenamiento
- Backups automáticos y panel de métricas

**Monitoreo:**
- Logs estructurados, alertas y métricas de desempeño


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