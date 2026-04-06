# 🎉 Aplicativo para event planners – Backend

API RESTful y servicio para la plataforma de gestión de eventos.  
Proporciona autenticación segura, gestión de eventos, usuarios, chat en tiempo real y roles.

> Proyecto de Software – Corporación Universitaria Iberoamericana (2026)

---

## ✨ Funcionalidades principales

- **Autenticación y autorización** con JWT y RBAC (roles: organizador, colaborador, visitante).
- **CRUD completo** de eventos, asistentes, terceros (clientes/proveedores).
- **Búsqueda avanzada** con filtros por texto, categoría, ubicación y fechas.
- **Sistema de mensajería** en tiempo real con gestión de conversaciones, bloqueos y archivado.
- **Generación de cotizaciones** en formato PDF.
- **Cumplimiento de la Ley 1581 de 2012** (protección de datos en Colombia).
- **Respaldos automáticos** diarios de la base de datos.

---

## 🛠️ Tecnologías utilizadas

| Área               | Tecnología                             |
|--------------------|----------------------------------------|
| Runtime            | Node.js                                |
| Framework          | Express.js                             |
| Base de datos      | PostgreSQL (recomendado) / MongoDB     |
| ORM / ODM          | Sequelize (PostgreSQL) / Mongoose      |
| Autenticación      | JWT + bcryptjs                         |

---

## 📦 Requisitos previos

- Node.js (v18 o superior)
- PostgreSQL (v14+) o MongoDB (v5+)
- npm o yarn
