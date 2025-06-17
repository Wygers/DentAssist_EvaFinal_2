# 🦷 DentAssist - Sistema de Gestión Clínica Dental "Sonrisa Plena"

**Versión MVP funcional - Proyecto Académico ASP.NET Core MVC**

## 📘 Descripción General

**DentAssist** es una aplicación web desarrollada para digitalizar la gestión clínica y administrativa de la clínica dental "Sonrisa Plena". La versión actual incluye funcionalidades completas para gestionar **pacientes, odontólogos, turnos y tratamientos**, resolviendo problemáticas críticas derivadas de la gestión manual anterior.

---

## 🎯 Objetivo del Proyecto

- Centralizar la información clínica y administrativa.
- Optimizar la gestión de turnos, profesionales y pacientes.
- Implementar arquitectura MVC con Entity Framework Core.
- Establecer una base escalable para futuras mejoras (plan de tratamiento, autenticación, reportes).

---

## 🧩 Funcionalidades Implementadas

| Módulo         | Estado | Detalle |
|----------------|--------|---------|
| **Pacientes**  | ✅     | Alta, baja, modificación y listado con validaciones |
| **Odontólogos**| ✅     | Gestión completa: nombre, matrícula, especialidad |
| **Turnos**     | ✅     | Asignación con estado, fecha y duración por paciente y profesional |
| **Tratamientos**| ✅    | ABM completo de servicios clínicos prestados |
| **Plan de tratamiento** | ❌     | No implementado en esta versión |
| **Autenticación por roles** | ❌ | No disponible aún (sin login) |

---

## 👨‍⚕️ Roles Simulados

Aunque no se implementó dentro de la aplicación control de acceso por roles, las vistas están organizadas para simular el flujo de trabajo por perfiles:

- **Administrador**: gestiona odontólogos y tratamientos.
- **Recepcionista**: registra pacientes y turnos.
- **Odontólogo**: consulta agenda y ficha clínica del paciente (acceso indirecto).

---

## 🛠️ Tecnologías Utilizadas

- **Frontend**: Razor Pages + Bootstrap 5
- **Backend**: ASP.NET Core MVC (.NET 6)
- **ORM**: Entity Framework Core (Code First con migraciones)
- **Base de datos**: SQL Server / LocalDB
- **Control de versiones**: Git (local o GitHub opcional)

---

## ⚙️ Instrucciones de Instalación

### Requisitos Previos

- Visual Studio 2022 o superior
- .NET 6 SDK
- SQL Server Express o LocalDB

### Pasos

1. Clonar el repositorio:

   ```bash
   git clone https://github.com/usuario/DentAssist.git
