# Jorge Alejandro Molina Carrera
### DBA Senior · SQL Server Expert · IT Leader · Guatemala 🇬🇹

---

## 👨‍💻 Sobre mí

Especialista en administración y optimización de bases de datos con **18+ años de experiencia** en entornos de producción. Actualmente administro **32 bases de datos en 5 motores distintos** en una organización de 3,400 empleados.

Creo en datos bien administrados como base de cualquier sistema confiable. Mi enfoque: prevenir antes que apagar incendios, optimizar con evidencia (execution plans, DMVs), y documentar lo que sé para que otros puedan aprender.

---

## 🗄️ Motores en producción

| Motor | BDs | Rol |
|---|---|---|
| SQL Server 2008–2019 | 25 | Administración completa |
| DB2 iSeries | 6 | Administración |
| MySQL | 1 | Integración con plataforma web |
| Sybase | 1 | Administración |
| SSAS (OLAP) | 1 | Cubos multidimensionales para BI |

---

## 🛠️ Stack técnico

**Bases de datos**
`SQL Server` `T-SQL` `SSRS` `SSIS` `SSAS` `DB2` `MySQL` `Oracle PL/SQL` `Sybase` `MariaDB`

**Capacidades DBA**
`Performance Tuning` `Execution Plans` `Wait Statistics` `Índices` `Particionamiento` `TDE` `Auditoría` `SQL Agent Jobs` `Backup & Recovery` `DMVs` `Migraciones`

**Desarrollo & BI**
`Genexus 7.5–18` `Power BI` `Python (Pandas · NumPy)` `PowerShell` `Git` `SSIS/TOS (ETL)`

**Gestión**
`SCRUM` `RUP` `Project Management` `Liderazgo de equipos`

---

## 📌 Caso de estudio — Optimización RBAR → Set-based

**Problema:** Proceso de afiliaciones corría en Genexus con lógica registro por registro (~20 queries por ciclo). Tiempo de ejecución: **días**.

**Diagnóstico:** Anti-patrón RBAR (*Row By Agonizing Row*) — overhead masivo de red y contexto por cada iteración.

**Solución:** Migración completa a stored procedures con procesamiento en lote (set-based). Una sola operación de conjunto reemplazó miles de llamadas individuales.

**Resultado:** Tiempo de procesamiento reducido de **días a minutos**.

> 📁 Ver implementación genérica → [`sql-performance-patterns`](https://github.com/jorgemolina777/sql-performance-patterns)

---

## 🚨 Protocolo de restauración de emergencia

Cuando una BD falla en producción, el orden importa:

```
1. COMUNICAR   → Jefaturas + áreas operativas afectadas
2. PAUSAR      → Detener operaciones para evitar corrupción adicional
3. EVALUAR     → Identificar tipo de fallo y backup más reciente viable
4. RESTAURAR   → En paralelo, con nombre alterno (sin afectar producción)
5. RECUPERAR   → Trasladar datos válidos de la BD original si es posible
6. VALIDAR     → Usuario clave del área confirma integridad de datos
7. HABILITAR   → Permisos y acceso restaurados
```

*El procedimiento varía según el tipo de fallo: corrupción, pérdida de datos o fallo de hardware.*

---

## 🌍 Proyectos destacados

### 🔴 AlertaGT — Mapa de seguridad ciudadana
Sistema de análisis en tiempo real que procesaba hashtags de Twitter asociados a inseguridad para generar un **mapa de calor georreferenciado** de zonas peligrosas en Guatemala. Proyecto de tesis de grado.

`Python` `Twitter API` `Geomapas` `Análisis de texto`

---

## 🏆 Trayectoria

```
2018 – hoy   IRTRA (3,400 empleados)      → Jefe Análisis y Programación / DBA
2015 – 2018  FINCA Network Support B.V.   → Implementation & Analysis Engineer
2013 – 2015  FINCA International / MFSI   → Regional Implementation Engineer
2009 – 2013  Micro Finance Solutions Inc. → Supervisor de Desarrollo
```

**Operaciones internacionales:** Guatemala · Nicaragua · Honduras · México · El Salvador · Zambia

---

## 📜 Certificaciones

- 🏅 **Certificación SQL Server 2019 — Microsoft**
- 📚 T-SQL · Administración · Data Warehouse (SQL Server 2016 — AgeXport/Galileo)
- 🎓 Diplomado de Supervisión — INTECAP

---

## 📫 Contacto

[![LinkedIn](https://img.shields.io/badge/LinkedIn-jorgemolina777-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/jorgemolina777)
[![Email](https://img.shields.io/badge/Email-JorgeMolina777%40gmail.com-D14836?style=flat&logo=gmail)](mailto:JorgeMolina777@gmail.com)

---

*"Un DBA no solo guarda datos — garantiza que el negocio pueda operar mañana."*
