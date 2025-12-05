# PMBOK 7 - Guía Práctica y Caso de Aplicación

## 📚 ¿Qué es PMBOK 7?

La **Guía del PMBOK® 7ma Edición** (2021) representa un cambio paradigmático en la gestión de proyectos, pasando de un enfoque basado en **procesos** a uno basado en **principios** y **dominios de desempeño**.

### Cambios Clave vs PMBOK 6
| PMBOK 6 | PMBOK 7 |
|---------|---------|
| 49 Procesos | 12 Principios |
| 10 Áreas de Conocimiento | 8 Dominios de Desempeño |
| Enfoque predictivo | Enfoque adaptativo/híbrido |
| Prescriptivo | Orientado a resultados |

---

## 🎯 Los 12 Principios de PMBOK 7

```
┌─────────────────────────────────────────────────────────────────┐
│                    12 PRINCIPIOS DE PMBOK 7                      │
├─────────────────────────────────────────────────────────────────┤
│  1. Ser un administrador diligente, respetuoso y cuidadoso      │
│  2. Crear un entorno colaborativo del equipo                     │
│  3. Involucrarse eficazmente con los interesados                │
│  4. Enfocarse en el valor                                        │
│  5. Reconocer, evaluar y responder a las interacciones          │
│  6. Demostrar comportamientos de liderazgo                       │
│  7. Adaptar según el contexto                                    │
│  8. Incorporar la calidad en procesos y entregables             │
│  9. Navegar en la complejidad                                    │
│ 10. Optimizar las respuestas a los riesgos                      │
│ 11. Adoptar la adaptabilidad y resiliencia                      │
│ 12. Permitir el cambio para lograr el estado futuro previsto    │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🔷 Los 8 Dominios de Desempeño

```
                    ┌─────────────────┐
                    │  INTERESADOS    │
                    └────────┬────────┘
                             │
        ┌────────────────────┼────────────────────┐
        │                    │                    │
        ▼                    ▼                    ▼
┌───────────────┐   ┌───────────────┐   ┌───────────────┐
│    EQUIPO     │   │  ENFOQUE DE   │   │  PLANIFICA-   │
│               │   │  DESARROLLO   │   │     CIÓN      │
└───────┬───────┘   └───────┬───────┘   └───────┬───────┘
        │                   │                   │
        └───────────────────┼───────────────────┘
                            │
                            ▼
                ┌───────────────────────┐
                │   TRABAJO DEL         │
                │     PROYECTO          │
                └───────────┬───────────┘
                            │
        ┌───────────────────┼───────────────────┐
        │                   │                   │
        ▼                   ▼                   ▼
┌───────────────┐   ┌───────────────┐   ┌───────────────┐
│   ENTREGA     │   │   MEDICIÓN    │   │ INCERTIDUMBRE │
│               │   │               │   │               │
└───────────────┘   └───────────────┘   └───────────────┘
```

---

## 🏢 CASO PRÁCTICO: Implementación de Sistema ERP

### Contexto del Proyecto
**Empresa:** TechCorp S.A. (Empresa manufacturera mediana)
**Proyecto:** Implementación de SAP S/4HANA
**Duración estimada:** 18 meses
**Presupuesto:** $2,500,000 USD
**Equipo:** 25 personas (internos + consultores)

---

## 📋 Aplicación de los 8 Dominios de Desempeño

### 1️⃣ DOMINIO: INTERESADOS (Stakeholders)

#### Identificación de Interesados
| Interesado | Rol | Interés | Influencia | Estrategia |
|------------|-----|---------|------------|------------|
| CEO | Patrocinador Ejecutivo | Alto | Alto | Gestionar de cerca |
| CFO | Sponsor Financiero | Alto | Alto | Gestionar de cerca |
| CIO | Líder Técnico | Alto | Alto | Gestionar de cerca |
| Gerentes de Área | Usuarios Clave | Alto | Medio | Mantener satisfechos |
| Usuarios Finales | Operadores | Medio | Bajo | Mantener informados |
| Proveedor SAP | Partner | Alto | Medio | Mantener satisfechos |
| Sindicato | Representante | Medio | Medio | Monitorear |

#### Matriz Poder/Interés
```
         ALTO  │ Mantener      │ Gestionar
    P          │ Satisfechos   │ de Cerca
    O    ──────┼───────────────┼───────────────
    D          │               │
    E    BAJO  │ Monitorear    │ Mantener
    R          │               │ Informados
               └───────────────┴───────────────
                     BAJO            ALTO
                        INTERÉS
```

#### Plan de Involucramiento
```yaml
Comunicación:
  CEO/CFO:
    - Frecuencia: Quincenal
    - Formato: Reunión ejecutiva + Dashboard
    - Contenido: KPIs, riesgos críticos, decisiones pendientes
  
  Gerentes de Área:
    - Frecuencia: Semanal
    - Formato: Comité de seguimiento
    - Contenido: Avance por módulo, issues, capacitación
  
  Usuarios Finales:
    - Frecuencia: Mensual
    - Formato: Newsletter + Town Hall
    - Contenido: Beneficios, cronograma, preparación
```

---

### 2️⃣ DOMINIO: EQUIPO (Team)

#### Estructura del Equipo
```
                    ┌─────────────────┐
                    │  SPONSOR (CFO)  │
                    └────────┬────────┘
                             │
                    ┌────────┴────────┐
                    │  PROJECT        │
                    │  MANAGER        │
                    └────────┬────────┘
                             │
        ┌────────────────────┼────────────────────┐
        │                    │                    │
        ▼                    ▼                    ▼
┌───────────────┐   ┌───────────────┐   ┌───────────────┐
│  LÍDER        │   │  LÍDER        │   │  LÍDER        │
│  FUNCIONAL    │   │  TÉCNICO      │   │  CAMBIO       │
│  (5 personas) │   │  (8 personas) │   │  (4 personas) │
└───────────────┘   └───────────────┘   └───────────────┘
        │                    │                    │
        ▼                    ▼                    ▼
   - Finanzas           - Desarrollo        - Capacitación
   - Ventas             - Integraciones     - Comunicación
   - Compras            - Migraciones       - Soporte
   - Producción         - Infraestructura   - Documentación
   - RRHH
```

#### Modelo de Liderazgo Situacional
| Fase del Proyecto | Estilo de Liderazgo | Acciones |
|-------------------|---------------------|----------|
| Inicio | Directivo | Definir roles, establecer reglas |
| Planificación | Coaching | Guiar, desarrollar competencias |
| Ejecución | Participativo | Delegar, empoderar decisiones |
| Cierre | Delegativo | Autonomía, reconocimiento |

#### Desarrollo del Equipo
```yaml
Capacitación:
  Técnica:
    - SAP S/4HANA Fundamentals (40 hrs)
    - Módulos específicos (80 hrs c/u)
    - ABAP para desarrolladores (60 hrs)
  
  Metodológica:
    - PMBOK 7 Essentials (16 hrs)
    - Agile/Scrum (24 hrs)
    - Gestión del Cambio (16 hrs)

Team Building:
  - Kick-off presencial (2 días)
  - Retrospectivas mensuales
  - Celebración de hitos
```

---

### 3️⃣ DOMINIO: ENFOQUE DE DESARROLLO (Development Approach)

#### Selección del Enfoque: HÍBRIDO
```
┌─────────────────────────────────────────────────────────────────┐
│                    ENFOQUE HÍBRIDO                               │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│   PREDICTIVO                              ÁGIL                   │
│   (Waterfall)                            (Scrum)                 │
│                                                                  │
│   ┌─────────────┐                    ┌─────────────┐            │
│   │ Infraestruc-│                    │ Configura-  │            │
│   │ tura & HW   │                    │ ción SAP    │            │
│   ├─────────────┤                    ├─────────────┤            │
│   │ Migraciones │                    │ Desarrollos │            │
│   │ de Datos    │                    │ Custom      │            │
│   ├─────────────┤                    ├─────────────┤            │
│   │ Contratos & │                    │ Pruebas     │            │
│   │ Licencias   │                    │ UAT         │            │
│   └─────────────┘                    └─────────────┘            │
│                                                                  │
│   Entregables fijos                  Sprints de 3 semanas       │
│   Fechas comprometidas               Backlog priorizado         │
│   Documentación formal               Demos frecuentes           │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

#### Ciclo de Vida del Proyecto
```
Fase 1: PREPARACIÓN (3 meses)
├── Kick-off y gobernanza
├── Análisis de procesos AS-IS
├── Definición de alcance
└── Adquisición de infraestructura

Fase 2: DISEÑO (4 meses)
├── Diseño de procesos TO-BE
├── Configuración base SAP
├── Diseño de integraciones
└── Plan de migración de datos

Fase 3: CONSTRUCCIÓN (6 meses) [ÁGIL - Sprints]
├── Sprint 1-4: Módulo Finanzas
├── Sprint 5-8: Módulo Ventas/Compras
├── Sprint 9-12: Módulo Producción
└── Sprint 13-16: Integraciones

Fase 4: PRUEBAS (3 meses)
├── Pruebas unitarias
├── Pruebas de integración
├── UAT (User Acceptance Testing)
└── Pruebas de rendimiento

Fase 5: GO-LIVE (2 meses)
├── Migración final de datos
├── Capacitación usuarios
├── Cutover y Go-Live
└── Soporte post-implementación
```

---

### 4️⃣ DOMINIO: PLANIFICACIÓN (Planning)

#### Estructura de Desglose del Trabajo (EDT/WBS)
```
1. PROYECTO ERP SAP S/4HANA
│
├── 1.1 GESTIÓN DEL PROYECTO
│   ├── 1.1.1 Plan de Proyecto
│   ├── 1.1.2 Informes de Avance
│   ├── 1.1.3 Gestión de Cambios
│   └── 1.1.4 Cierre del Proyecto
│
├── 1.2 PREPARACIÓN
│   ├── 1.2.1 Kick-off
│   ├── 1.2.2 Análisis AS-IS
│   ├── 1.2.3 Definición de Alcance
│   └── 1.2.4 Infraestructura
│
├── 1.3 DISEÑO
│   ├── 1.3.1 Procesos TO-BE
│   ├── 1.3.2 Configuración Base
│   ├── 1.3.3 Arquitectura Técnica
│   └── 1.3.4 Plan de Migración
│
├── 1.4 CONSTRUCCIÓN
│   ├── 1.4.1 Módulo FI/CO (Finanzas)
│   ├── 1.4.2 Módulo SD (Ventas)
│   ├── 1.4.3 Módulo MM (Compras)
│   ├── 1.4.4 Módulo PP (Producción)
│   ├── 1.4.5 Integraciones
│   └── 1.4.6 Desarrollos ABAP
│
├── 1.5 PRUEBAS
│   ├── 1.5.1 Pruebas Unitarias
│   ├── 1.5.2 Pruebas Integración
│   ├── 1.5.3 UAT
│   └── 1.5.4 Pruebas Rendimiento
│
├── 1.6 DESPLIEGUE
│   ├── 1.6.1 Migración Datos
│   ├── 1.6.2 Capacitación
│   ├── 1.6.3 Go-Live
│   └── 1.6.4 Soporte Post-Go-Live
│
└── 1.7 GESTIÓN DEL CAMBIO
    ├── 1.7.1 Comunicación
    ├── 1.7.2 Capacitación
    └── 1.7.3 Adopción
```

#### Cronograma de Alto Nivel (Gantt Simplificado)
```
                    2024                              2025
            Q1      Q2      Q3      Q4      Q1      Q2
            ├───────┼───────┼───────┼───────┼───────┼───────┤
Preparación ████████
Diseño              ████████████████
Construcción                        ████████████████████████
Pruebas                                             ████████████
Go-Live                                                     ████████
Soporte                                                         ████
            ├───────┼───────┼───────┼───────┼───────┼───────┤
Hitos:      H1      H2              H3      H4      H5      H6

H1: Kick-off completado
H2: Diseño aprobado
H3: Fin construcción Finanzas
H4: Fin construcción completa
H5: UAT aprobado
H6: Go-Live exitoso
```

#### Presupuesto por Fase
| Fase | Presupuesto | % del Total |
|------|-------------|-------------|
| Preparación | $200,000 | 8% |
| Diseño | $350,000 | 14% |
| Construcción | $1,100,000 | 44% |
| Pruebas | $300,000 | 12% |
| Despliegue | $400,000 | 16% |
| Contingencia | $150,000 | 6% |
| **TOTAL** | **$2,500,000** | **100%** |

---

### 5️⃣ DOMINIO: TRABAJO DEL PROYECTO (Project Work)

#### Procesos de Ejecución
```yaml
Gestión del Trabajo Diario:
  Daily Standup:
    - Duración: 15 minutos
    - Participantes: Equipo técnico
    - Preguntas: ¿Qué hice? ¿Qué haré? ¿Impedimentos?
  
  Sprint Planning:
    - Frecuencia: Cada 3 semanas
    - Duración: 4 horas
    - Output: Sprint Backlog comprometido
  
  Sprint Review:
    - Frecuencia: Fin de cada sprint
    - Participantes: Equipo + Stakeholders
    - Output: Demo de funcionalidades

Control de Calidad:
  Code Review:
    - Obligatorio para todo desarrollo ABAP
    - Mínimo 2 revisores
    - Checklist de estándares
  
  Testing:
    - Cobertura mínima: 80%
    - Pruebas automatizadas donde sea posible
    - Documentación de casos de prueba
```

#### Gestión de Impedimentos
| Prioridad | Tiempo de Respuesta | Escalamiento |
|-----------|---------------------|--------------|
| Crítico | 2 horas | PM → Sponsor |
| Alto | 8 horas | PM → Líder de Área |
| Medio | 24 horas | Líder de Equipo |
| Bajo | 48 horas | Equipo |

---

### 6️⃣ DOMINIO: ENTREGA (Delivery)

#### Criterios de Aceptación por Módulo
```yaml
Módulo Finanzas (FI/CO):
  Funcionales:
    - Contabilidad general operativa
    - Cuentas por pagar/cobrar funcionando
    - Reportes financieros generados correctamente
    - Cierre mensual ejecutable en < 2 días
  
  Técnicos:
    - Tiempo de respuesta < 3 segundos
    - Integración con bancos validada
    - Migración de saldos verificada
  
  Documentación:
    - Manual de usuario aprobado
    - Procedimientos documentados
    - Material de capacitación listo

Módulo Ventas (SD):
  Funcionales:
    - Ciclo completo de venta operativo
    - Facturación electrónica integrada
    - Reportes de ventas disponibles
  
  Técnicos:
    - Integración con CRM validada
    - Performance en picos de demanda
```

#### Definition of Done (DoD)
```
✅ Código desarrollado y revisado
✅ Pruebas unitarias pasadas (>80% cobertura)
✅ Pruebas de integración pasadas
✅ Documentación técnica actualizada
✅ Manual de usuario creado/actualizado
✅ Aprobación del Product Owner
✅ Desplegado en ambiente de QA
✅ Sin defectos críticos o altos abiertos
```

#### Entregables por Fase
| Fase | Entregables Clave |
|------|-------------------|
| Preparación | Project Charter, Análisis AS-IS, Plan de Proyecto |
| Diseño | Blueprint, Arquitectura, Plan de Migración |
| Construcción | Sistema configurado, Desarrollos, Integraciones |
| Pruebas | Reportes de pruebas, Defectos resueltos, Sign-off UAT |
| Despliegue | Sistema en producción, Usuarios capacitados, Documentación |

---

### 7️⃣ DOMINIO: MEDICIÓN (Measurement)

#### KPIs del Proyecto
```yaml
Indicadores de Avance:
  SPI (Schedule Performance Index):
    - Fórmula: EV / PV
    - Meta: ≥ 0.95
    - Frecuencia: Semanal
  
  CPI (Cost Performance Index):
    - Fórmula: EV / AC
    - Meta: ≥ 0.95
    - Frecuencia: Semanal

Indicadores de Calidad:
  Defect Density:
    - Fórmula: Defectos / Puntos de función
    - Meta: < 0.5
  
  Test Coverage:
    - Meta: ≥ 80%
  
  UAT Pass Rate:
    - Meta: ≥ 95%

Indicadores de Equipo:
  Velocity:
    - Story Points completados por sprint
    - Tendencia: Estable o creciente
  
  Team Satisfaction:
    - Encuesta mensual
    - Meta: ≥ 4/5
```

#### Dashboard Ejecutivo
```
┌─────────────────────────────────────────────────────────────────┐
│                    DASHBOARD - PROYECTO ERP                      │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  AVANCE GENERAL          PRESUPUESTO           CRONOGRAMA       │
│  ┌──────────┐           ┌──────────┐          ┌──────────┐      │
│  │   67%    │           │  $1.6M   │          │  SPI     │      │
│  │  ████░░  │           │  de $2.5M│          │  0.98    │      │
│  │ On Track │           │   64%    │          │    ✓     │      │
│  └──────────┘           └──────────┘          └──────────┘      │
│                                                                  │
│  RIESGOS                 ISSUES               CAMBIOS           │
│  ┌──────────┐           ┌──────────┐          ┌──────────┐      │
│  │ 🔴 2     │           │ Abiertos │          │ Pendien- │      │
│  │ 🟡 5     │           │    8     │          │ tes: 3   │      │
│  │ 🟢 12    │           │ Críticos │          │ Aproba-  │      │
│  │          │           │    1     │          │ dos: 12  │      │
│  └──────────┘           └──────────┘          └──────────┘      │
│                                                                  │
│  PRÓXIMOS HITOS                                                  │
│  ├── Sprint 10 Review ────────────── 15 Mar 2025                │
│  ├── Fin Módulo Producción ───────── 30 Mar 2025                │
│  └── Inicio UAT ──────────────────── 15 Abr 2025                │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

#### Valor Ganado (EVM)
| Métrica | Fórmula | Valor Actual | Estado |
|---------|---------|--------------|--------|
| PV (Planned Value) | Presupuesto planificado | $1,700,000 | - |
| EV (Earned Value) | Trabajo completado | $1,666,000 | - |
| AC (Actual Cost) | Costo real | $1,600,000 | - |
| SV (Schedule Variance) | EV - PV | -$34,000 | ⚠️ |
| CV (Cost Variance) | EV - AC | +$66,000 | ✅ |
| SPI | EV / PV | 0.98 | ⚠️ |
| CPI | EV / AC | 1.04 | ✅ |
| EAC (Estimate at Completion) | BAC / CPI | $2,403,846 | ✅ |

---

### 8️⃣ DOMINIO: INCERTIDUMBRE (Uncertainty)

#### Registro de Riesgos
| ID | Riesgo | Prob. | Impacto | Score | Respuesta | Responsable |
|----|--------|-------|---------|-------|-----------|-------------|
| R01 | Resistencia al cambio de usuarios | Alta | Alto | 🔴 | Mitigar: Plan de gestión del cambio intensivo | Líder Cambio |
| R02 | Retrasos en migración de datos | Media | Alto | 🟡 | Mitigar: Pruebas tempranas, plan de contingencia | Líder Técnico |
| R03 | Rotación de personal clave | Media | Alto | 🟡 | Transferir: Documentación, backup de roles | PM |
| R04 | Cambios de alcance frecuentes | Alta | Medio | 🟡 | Evitar: Proceso formal de control de cambios | PM |
| R05 | Problemas de integración con sistemas legacy | Media | Medio | 🟡 | Mitigar: POC temprano, APIs bien definidas | Líder Técnico |
| R06 | Falta de disponibilidad de usuarios clave | Media | Medio | 🟡 | Mitigar: Calendario acordado, backups | Líder Funcional |
| R07 | Subestimación de desarrollos custom | Baja | Alto | 🟡 | Aceptar: Contingencia en presupuesto | PM |
| R08 | Problemas de rendimiento en producción | Baja | Alto | 🟡 | Mitigar: Pruebas de carga, sizing adecuado | Líder Técnico |

#### Matriz de Probabilidad e Impacto
```
         │  Bajo   │  Medio  │  Alto   │
─────────┼─────────┼─────────┼─────────┤
  Alta   │   🟡    │   🟡    │   🔴    │
─────────┼─────────┼─────────┼─────────┤
  Media  │   🟢    │   🟡    │   🟡    │
─────────┼─────────┼─────────┼─────────┤
  Baja   │   🟢    │   🟢    │   🟡    │
─────────┴─────────┴─────────┴─────────┘
              IMPACTO
```

#### Plan de Respuesta a Riesgos Críticos
```yaml
R01 - Resistencia al Cambio:
  Estrategia: MITIGAR
  Acciones:
    - Identificar champions por área
    - Comunicación temprana y frecuente
    - Involucrar usuarios en diseño
    - Quick wins visibles
    - Capacitación hands-on
  Trigger: Encuestas de clima < 3/5
  Plan de Contingencia: Soporte intensivo post go-live

R02 - Retrasos en Migración:
  Estrategia: MITIGAR
  Acciones:
    - Pruebas de migración desde Fase 2
    - Limpieza de datos previa
    - Herramientas automatizadas
    - Equipo dedicado
  Trigger: Prueba de migración falla > 2 veces
  Plan de Contingencia: Go-live parcial, migración por fases
```

#### Oportunidades Identificadas
| ID | Oportunidad | Prob. | Impacto | Estrategia |
|----|-------------|-------|---------|------------|
| O01 | Automatización de procesos adicionales | Media | Alto | Explotar: Incluir en alcance |
| O02 | Reducción de licencias legacy | Alta | Medio | Explotar: Negociar cancelación |
| O03 | Mejora en reportería con SAP Analytics | Media | Medio | Mejorar: POC en paralelo |

---

## 📊 Aplicación de los 12 Principios en el Proyecto

|