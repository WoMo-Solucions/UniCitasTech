# 🎓 UniCitasTech  
## Sistema Integral de Gestión de Tutorías Universitarias

![Estado](https://img.shields.io/badge/🚀_En_Desarrollo-blue) ![Licencia](https://img.shields.io/badge/Licencia-🔒_Privada-red) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-Auth_%26_DB-3ECF8E?logo=supabase&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![n8n](https://img.shields.io/badge/n8n-Automation-orange?logo=n8n&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-Containerization-2496ED?logo=docker&logoColor=white) ![Render](https://img.shields.io/badge/Render-Cloud_Deploy-0099FF?logo=render&logoColor=white)

## 📋 Descripción del Sistema
Solución para **gestión inteligente de tutorías universitarias**: reservas digitales, disponibilidad en tiempo real y notificaciones automáticas.  
**Jerarquía:** Hijo de **AgenDarte** (usa su base de agendamiento y extiende el dominio académico).

Incluye:
- Registro y autenticación con Supabase Auth (estudiantes/tutores/administración)
- Catálogos de carreras, materias y tutores
- Bloqueo automático de horarios reservados
- Notificaciones por correo (n8n + Gmail)  
- Interfaz responsive y accesible

## 🛠 Stack Tecnológico
**Backend:** Flask (Python 3.10+), JWT/RBAC  
**Base de Datos:** PostgreSQL en **Supabase** (Auth + RLS + Storage + REST)  
**Frontend:** HTML5, CSS3 (Bootstrap 5), JavaScript (ES6+)  
**Automatizaciones:** **n8n** (recordatorios / reportes / integraciones)

## 🖥️ Infraestructura
**Render (Producción):**
- Servicios separados: `frontend`, `backend`, `n8n` (todos en **Docker**)
- HTTPS forzado, variables de entorno seguras

**Supabase:**
- PostgreSQL gestionado con políticas **RLS**, autenticación, storage
- Backups automáticos y panel de métricas

**Monitoreo:**
- Logs estructurados, alertas y métricas de desempeño

## 🖥️ Estructura del Proyecto
📁 UniCitasTech  
├── 📂 data/                 # Catálogo inicial (carreras/materias)  
├── 📂 static/  
│   ├── 📂 css/              # Estilos  
│   ├── 📂 js/               # Lógica de reservas y auth  
│   └── 📂 img/              # Logos / assets  
├── 📂 templates/  
│   ├── index.html           # Login / Registro  
│   └── dashboard.html       # Panel de reservas  
├── 📂 backend/  
│   ├── app.py               # API principal (Flask)  
│   ├── routes/              # Endpoints (reservas, tutores, etc.)  
│   └── services/            # Reglas de negocio  
└── 📂 docs/                  # Documentación y esquema SQL

## 🔍 Características Clave
- Reservas únicas por tutor/fecha/hora  
- Panel para bienestar/coord. académica  
- Correos de confirmación/cancelación  
- Reportes de uso y demanda por materia  
- Responsive para móviles

## 🛡️ Seguridad Avanzada
- Supabase Auth + JWT (scopes por rol)  
- RLS en tablas críticas (estudiantes/tutores/reservas)  
- Service Role Key solo en backend/n8n  
- Rate limit a endpoints de reserva

## 📊 Métricas de Rendimiento
- Latencia objetivo <250ms  
- 99.9% de disponibilidad  
- 500 usuarios concurrentes estimados

## 📝 Gestión de Versiones
- GitFlow, versionado semántico  
- CI/CD con Render  
- Migraciones con scripts SQL en `docs/`

💡 **Notas Técnicas:**  
✅ Reutiliza base de agendamiento (AgenDarte)  
✅ Amplía dominio a educación universitaria  
✅ N8n para recordatorios y reportes  
✅ Estructura lista para PWA

“Educación conectada, sin papeleo y sin esperas.”

## 📬 Contacto Corporativo
**Julián Alberto Ramírez**  
💻 Socio Fundador & Visionario Tecnológico  
<img width="222" height="29" alt="Logo WSˢ" src="https://github.com/user-attachments/assets/24519130-f605-4762-a4f2-374c450f2b64" />  
🏢 **WoMo Soluciónˢ – Soluciones Tecnológicas Avanzadas**  

📅 **Control de Versiones**  
![Versión](https://img.shields.io/badge/Versión-1.0.0-blue) ![Última_Actualización](https://img.shields.io/badge/Actualizado-Oct_2025-green)
