# Intrusión en servidores que contienen datos personales

La intrusión en servidores que contienen datos personales activa un complejo régimen de responsabilidades, principalmente en el ámbito **administrativo** (por incumplimiento de las obligaciones de seguridad de la entidad que custodia los datos) y, potencialmente, en el ámbito **penal** (por el acto de acceso ilícito perpetrado por el intruso).

A continuación, se desarrolla la investigación en los dos apartados solicitados, basándose en la **Ley Orgánica de Protección de Datos Personales y garantía de los derechos digitales (LOPDGDD)**, el **Reglamento General de Protección de Datos (RGPD)**, la **Ley de Servicios de la Sociedad de la Información y de Comercio Electrónico (LSSI)** y la **Ley de Propiedad Intelectual (LPI)**.

---

## 1. Investigar las sanciones aplicables a la intrusión en servidores que contienen datos personales

La intrusión en servidores que almacenan datos personales constituye una **violación de la seguridad de los datos personales** que afecta directamente al principio de integridad y confidencialidad, y genera consecuencias administrativas para el responsable o el encargado del tratamiento.

### A. Sanciones Administrativas (RGPD y LOPDGDD)

El régimen sancionador se centra en la responsabilidad del **responsable o encargado del tratamiento** por no garantizar un nivel de seguridad adecuado.

| **Criterio** | **Descripción y Fundamento Legal** |
|---------------|------------------------------------|
| **Tipo de Infracción** | La falta de adopción de medidas técnicas y organizativas apropiadas para garantizar un nivel de seguridad adecuado al riesgo del tratamiento (Art. 32.1 RGPD) se considera una infracción **grave**. Las infracciones que vulneren los principios de protección de datos (Art. 5 RGPD), incluyendo integridad y confidencialidad, se consideran **muy graves**. |
| **Cuantía de las Multas** | Según el Art. 83 del RGPD: <br> - **Infracciones Graves** (Art. 83.4): Hasta **10 millones €** o el **2 %** del volumen de negocio anual global. <br> - **Infracciones Muy Graves** (Art. 83.5): Hasta **20 millones €** o el **4 %** del volumen de negocio anual global. |
| **Criterios de Graduación** | Se valoran la naturaleza, gravedad y duración de la infracción, el número de afectados, el daño causado, y si el infractor notificó la infracción o adoptó medidas correctivas. |
| **Medidas Correctivas** | Las autoridades (AEPD o autonómicas) pueden: <br> • Apercibir o amonestar. <br> • Ordenar ajustar el tratamiento al Reglamento. <br> • Limitar o prohibir el tratamiento. <br> • Obligar a comunicar la violación al interesado. |
| **Obligaciones de Notificación** | El responsable debe notificar la violación a la autoridad en un máximo de **72 h** tras conocerla, salvo que no suponga riesgo para los derechos y libertades. Si el riesgo es alto, también debe notificarse a los afectados. El incumplimiento es infracción **grave**. |

---

### B. Sanciones y Responsabilidad Penal y Civil

La responsabilidad administrativa coexiste con otras responsabilidades:

1. **Responsabilidad Penal del Intruso:**  
   La LSSI establece que los prestadores de servicios están sujetos a la responsabilidad penal general del ordenamiento jurídico. La LPI no excluye las acciones penales aplicables.

2. **Responsabilidad Civil por Daños:**  
   Toda persona afectada por una infracción del RGPD tiene derecho a una **indemnización** por los daños materiales o inmateriales sufridos (Art. 82 RGPD).

---

## 2. Caso práctico: delito y consecuencias penales o administrativas

### Planteamiento del Caso Práctico

**Sujetos implicados:**
- **Responsable del Tratamiento (RT):** Clínica privada *Entidad Beta*, que gestiona datos de salud sin cifrado ni pseudonimización.  
- **Encargado del Tratamiento (ET):** Empresa de hosting *Entidad Gamma*, con menos de 250 empleados, sin registro de actividades de tratamiento.  
- **Tercero Ilícito (Intruso “X”):** Persona que explota una vulnerabilidad del servidor y accede a datos de salud de 10.000 pacientes.

**Delito e infracción:**
1. **Intrusión (ámbito penal):** El acceso y extracción de datos sin autorización constituye un **delito de acceso ilícito**.  
2. **Violación de seguridad (ámbito administrativo):** La falta de medidas de seguridad adecuadas infringe el **RGPD/LOPDGDD**.

---

### Posibles Consecuencias Penales y Administrativas

| **Consecuencia** | **Detalle y Fundamento Legal** |
|-------------------|--------------------------------|
| **I. Para el Intruso (X)** | **Responsabilidad Penal:** Sanciones por acceso ilícito y revelación de información. <br> **Responsabilidad Civil:** Indemnización a los pacientes afectados por daños y perjuicios. |
| **II. Para el Responsable (Clínica Beta)** | **Clasificación:** Muy grave. <br> - Tratamiento de datos de salud sin garantías adecuadas.<br> - Falta de medidas técnicas (Art. 32 RGPD).<br> - Omisión de notificación a la AEPD o a los afectados.<br> **Sanción:** Hasta 20 millones € o el 4 % del volumen de negocio global (Art. 83.5 RGPD).<br> **Medidas adicionales:** Prohibición temporal del tratamiento o inmovilización de datos. |
| **III. Para el Encargado (Hosting Gamma)** | **Clasificación:** Grave. <br> - Falta de registro de actividades de tratamiento (Art. 30 RGPD). <br> **Sanción:** Hasta 10 millones € o el 2 % del volumen de negocio global. <br> **Responsabilidad LSSI:** Incumplimiento de deberes de información sobre seguridad hacia los clientes. |

---

**Conclusión:**  
La intrusión en sistemas que manejan datos personales puede acarrear consecuencias graves tanto para el intruso (penales y civiles) como para las entidades responsables del tratamiento (administrativas y económicas). Cumplir las medidas del RGPD y la LOPDGDD es esencial para evitar sanciones y proteger los derechos de los afectados.