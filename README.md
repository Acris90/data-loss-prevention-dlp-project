# Políticas de Seguridad DLP

## 1. Introducción al Data Loss Prevention (DLP)

El **Data Loss Prevention (DLP)** o **Prevención de Pérdida de Datos** es un conjunto de estrategias, políticas y tecnologías diseñadas para evitar que la información sensible de una organización sea expuesta, filtrada o utilizada de forma no autorizada. Las soluciones DLP permiten identificar, monitorear y proteger los datos confidenciales, controlando cómo se accede a ellos, cómo se utilizan y cómo se transfieren dentro y fuera de la organización.

En un entorno empresarial moderno, las organizaciones manejan grandes volúmenes de información crítica, como datos personales de clientes, información financiera, propiedad intelectual o documentos estratégicos. La pérdida o filtración de estos datos puede generar consecuencias graves, incluyendo pérdidas económicas, daños reputacionales, sanciones legales o incumplimiento de normativas de protección de datos.

El DLP ayuda a mitigar estos riesgos mediante el establecimiento de políticas de seguridad que controlan el acceso a la información y supervisan el comportamiento de los usuarios. Estas políticas permiten detectar actividades sospechosas, bloquear transferencias no autorizadas y garantizar que los datos se utilicen únicamente para los fines previstos.

Además, el DLP se basa en principios fundamentales de seguridad de la información, como el **principio del menor privilegio**, que establece que los usuarios solo deben tener acceso a los recursos estrictamente necesarios para realizar su trabajo. De esta manera, se reduce la superficie de riesgo y se mejora la protección de la información sensible dentro de la organización.

---

# 2. Clasificación de Datos

Para aplicar correctamente las políticas de seguridad y protección de la información, la organización establecerá un sistema de **clasificación de datos basado en el nivel de sensibilidad de la información**. Esta clasificación permite determinar qué medidas de protección deben aplicarse y quién puede acceder a cada tipo de información.

Se establecen las siguientes categorías de clasificación:

## Datos Públicos

Los **datos públicos** son aquellos que pueden ser compartidos libremente sin generar riesgos para la organización.

### Ejemplos
- Información publicada en la página web corporativa  
- Material de marketing o publicidad  
- Comunicados de prensa  
- Información pública de productos o servicios  

### Nivel de protección
Bajo.

### Acceso
Disponible para cualquier persona dentro o fuera de la organización.

---

## Datos Internos

Los **datos internos** corresponden a información destinada únicamente al uso dentro de la organización. Aunque su exposición pública no necesariamente implica un impacto crítico, su acceso debe limitarse al personal autorizado.

### Ejemplos
- Procedimientos internos  
- Documentación operativa  
- Informes internos  
- Organigramas y documentación administrativa  

### Nivel de protección
Medio.

### Acceso
Restringido a empleados y personal autorizado de la organización.

---

## Datos Sensibles

Los **datos sensibles** incluyen información crítica cuya divulgación no autorizada podría generar daños significativos a la organización o a terceros.

### Ejemplos
- Datos personales de clientes o empleados  
- Información financiera o contable  
- Credenciales de acceso o información de autenticación  
- Propiedad intelectual  
- Contratos confidenciales  
- Información estratégica o comercial  

### Nivel de protección
Alto.

### Acceso
Limitado exclusivamente al personal autorizado que necesite dicha información para el desempeño de sus funciones.

---

# 3. Acceso y Control basado en el Principio del Menor Privilegio

La organización aplicará el **principio del menor privilegio (Least Privilege)** como base para la gestión de accesos a la información y a los sistemas.

Este principio establece que cada usuario debe disponer únicamente de los permisos mínimos necesarios para desempeñar sus tareas laborales. Limitar los privilegios reduce el riesgo de accesos indebidos, errores humanos o filtraciones de datos.

## Políticas de acceso

Las políticas de acceso a la información incluirán las siguientes medidas:

- Los permisos se asignarán en función del **rol del usuario dentro de la organización**.
- El acceso a datos sensibles requerirá **autorización adicional**.
- Los privilegios elevados serán limitados y supervisados.
- Los accesos serán revisados periódicamente para evitar acumulación de privilegios innecesarios.

## Roles responsables

La gestión y revisión de permisos será responsabilidad de distintos roles dentro de la organización:

**Departamento de TI**
- Gestiona la creación de cuentas de usuario.
- Asigna permisos iniciales.
- Administra los sistemas y plataformas de acceso.

**Responsable de Seguridad de la Información**
- Supervisa el cumplimiento de las políticas de acceso.
- Revisa accesos a información sensible.
- Investiga incidentes de seguridad.

**Responsables de departamento**
- Validan los permisos necesarios para sus empleados.
- Solicitan accesos específicos cuando es necesario.

**Recursos Humanos**
- Notifica altas, cambios de puesto y bajas de empleados.
- Garantiza que los accesos se ajusten a la situación laboral del usuario.

## Flujo de revisión de permisos

El proceso de asignación y revisión de permisos seguirá los siguientes pasos:

1. El responsable del departamento solicita el acceso necesario para el empleado.
2. El departamento de TI configura los permisos correspondientes.
3. El responsable de seguridad valida el acceso en caso de tratarse de datos sensibles.
4. Los accesos se documentan y registran.
5. Se realizarán revisiones periódicas de permisos para detectar accesos innecesarios.
6. Cuando un empleado cambia de puesto o abandona la organización, sus accesos se modificarán o revocarán inmediatamente.

---

# 4. Monitoreo y Auditoría

El monitoreo y la auditoría de las actividades relacionadas con datos sensibles son fundamentales para detectar accesos indebidos o posibles intentos de filtración de información.

La organización implementará mecanismos de supervisión que permitan registrar y analizar el uso de la información dentro de los sistemas.

## Reglas de monitoreo

Las actividades relacionadas con información sensible estarán sujetas a las siguientes reglas de monitoreo:

- Registro de accesos a archivos sensibles.
- Monitorización de descargas o copias masivas de información.
- Detección de transferencias de datos hacia dispositivos externos o servicios no autorizados.
- Registro de intentos de acceso denegados.
- Generación de alertas ante comportamientos anómalos.

## Auditoría de seguridad

Los registros generados por los sistemas serán utilizados para realizar auditorías de seguridad periódicas.

Estas auditorías permitirán:

- Identificar accesos sospechosos.
- Detectar actividades no autorizadas.
- Analizar posibles incidentes de seguridad.
- Generar evidencia para investigaciones internas.

Las revisiones de auditoría se realizarán de forma periódica, según la política de seguridad establecida por la organización.

## Herramientas de monitoreo

Para implementar estas capacidades, la organización puede utilizar diferentes herramientas de seguridad, como:

- **Sistemas SIEM (Security Information and Event Management)** para centralizar y analizar eventos de seguridad.
- **Soluciones DLP** que detecten intentos de fuga de información.
- **Sistemas de registro y auditoría del sistema operativo y aplicaciones**.

Estas herramientas permiten detectar comportamientos sospechosos y responder de forma temprana ante posibles incidentes.

---

# 5. Prevención de Filtraciones de Datos

Para reducir el riesgo de fuga de información confidencial, la organización implementará diversas medidas técnicas y organizativas orientadas a proteger los datos sensibles.

## Medidas técnicas

Entre las principales medidas de protección se incluyen:

- **Cifrado de datos en reposo y en tránsito** para evitar accesos no autorizados.
- Implementación de **soluciones DLP** que detecten intentos de transferencia de datos sensibles.
- **Control de acceso basado en roles** para limitar el acceso a información crítica.
- **Restricción del uso de dispositivos USB o almacenamiento removible** para evitar la copia de información confidencial.
- Control de transferencias de datos hacia servicios de almacenamiento en la nube no autorizados.
- Implementación de sistemas de alerta ante copias o transferencias masivas de información.

## Medidas organizativas

Además de las medidas tecnológicas, la organización aplicará políticas internas que refuercen la protección de la información:

- Procedimientos de aprobación para compartir datos sensibles.
- Revisión periódica de permisos de acceso.
- Definición de protocolos de respuesta ante incidentes de seguridad.
- Documentación y registro de actividades relacionadas con datos críticos.

---

# 6. Educación y Concienciación en Seguridad

La formación y concienciación del personal es un elemento fundamental para prevenir la pérdida de datos. Los empleados deben comprender la importancia de proteger la información y conocer las políticas de seguridad aplicables dentro de la organización.

La organización implementará programas de capacitación orientados a mejorar la cultura de seguridad entre los empleados.

## Programas de formación

Las iniciativas de formación incluirán:

- Formación inicial para nuevos empleados sobre políticas de seguridad.
- Sesiones periódicas de actualización en materia de ciberseguridad.
- Capacitación sobre clasificación de datos y manejo de información sensible.
- Información sobre riesgos asociados al uso de dispositivos externos o servicios no autorizados.

## Concienciación en seguridad

La organización también desarrollará campañas de concienciación que ayuden a reforzar las buenas prácticas de seguridad.

Estas acciones pueden incluir:

- Difusión de buenas prácticas de seguridad.
- Recordatorios sobre políticas internas.
- Simulaciones o ejercicios de seguridad.
- Material educativo sobre riesgos como phishing, fuga de información o uso indebido de datos.

El objetivo de estas iniciativas es fomentar una **cultura de seguridad**, en la que todos los empleados comprendan su papel en la protección de la información y colaboren activamente en la prevención de incidentes de seguridad.
