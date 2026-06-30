# 📖 Módulo 1: Introduction to Information Security

Este módulo establece los pilares teóricos fundamentales, la terminología industrial y las metodologías operativas indispensables para las auditorías de seguridad, el pentesting y las futuras operaciones de Red Team.

---

## 🏛️ 1. Pilares Básicos de InfoSec 

La seguridad de la información no se limita a proteger datos, sino a garantizar la resiliencia de toda la infraestructura corporativa mediante principios estrictos:

### La Tríada CIA (Áreas Core)
*   **Confidencialidad (Confidentiality):** Asegurar que solo las personas y procesos explícitamente autorizados tengan acceso a la información confidencial.
*   **Integridad (Integrity):** Garantizar que los datos permanezcan exactos y no sean modificados, destruidos o alterados de forma no autorizada o maliciosa.
*   **Disponibilidad (Availability):** Asegurar que los sistemas, redes y datos estén totalmente accesibles para los usuarios legítimos en el momento en que lo necesiten.

### Controles Corporativos Adicionales
*   **No repudio (Non-repudiation):** Garantizar que una parte no pueda negar la autoría de una acción, firma o mensaje enviado. Se implementa mediante firmas digitales y registros de auditoría (*logs*) inmutables.
*   **Autenticación (Authentication):** Mecanismos estrictos para verificar con certeza la identidad de un usuario, proceso o dispositivo (MFA, contraseñas, biométricos).
*   **Privacidad (Privacy):** El manejo adecuado, ético y bajo consentimiento legal para el procesamiento de datos personales sensibles.

---

## 🎯 2. El Núcleo: Riesgo, Amenaza y Vulnerabilidad

Para la redacción de reportes técnicos de Pentesting, es mandatorio dominar la diferencia exacta entre estos tres conceptos interconectados:

$$ Riesgo = Probabilidad \times Impacto $$

*   **Vulnerabilidad:** Es una debilidad inherente en el sistema, ya sea un fallo de software (bug), una mala configuración de red o una contraseña débil.
*   **Amenaza:** Es la causa potencial de un incidente; cualquier entidad, atacante o evento (malware, cibercriminales, desastres naturales) que intente explotar activamente una debilidad.
*   **Riesgo:** Es el potencial de daño cuantificable para la organización. Nace de la combinación de la probabilidad de que una amenaza descubra y explote una vulnerabilidad, junto con la gravedad del impacto financiero u operativo que cause.

---

## 🔄 3. El Ciclo de Procesos en Seguridad

La seguridad es un proceso continuo y dinámico estructurado en 7 fases estratégicas:
1.  **Evaluación de riesgos (*Risk Assessment*):** Identificar vulnerabilidades y medir su impacto potencial.
2.  **Planificación:** Crear las políticas de seguridad y asignar recursos.
3.  **Implementación de controles:** Desplegar soluciones técnicas preventivas y detectivas.
4.  **Monitoreo y detección:** Vigilar anomalías mediante herramientas centralizadas.
5.  **Respuesta a incidentes:** Contener, mitigar y aislar la amenaza tras un ataque detectado.
6.  **Recuperación ante desastres (*Disaster Recovery*):** Restaurar sistemas, respaldos y minimizar el tiempo de inactividad.
7.  **Mejora continua:** Auditar regularmente y aprender de los incidentes pasados para actualizar las defensas.

---

## 👥 4. Estructura Organizacional y Equipos

### Los Equipos de Trabajo 
*   **Red Team (Ofensivo):** Simula el comportamiento de adversarios y atacantes reales del mundo real para poner a prueba de forma crítica los controles defensivos.
*   **Blue Team (Defensivo):** Responsables de la seguridad interna, encargados de monitorizar, detectar anomalías y defender la infraestructura contra los ataques.
*   **Purple Team (Conjunto):** Cooperación e integración directa entre atacantes y defensores para optimizar la postura de seguridad de forma acelerada.

### Roles Clave en la Industria
*   **CISO (Chief Information Security Officer):** Diseña la estrategia global de seguridad y asegura la alineación con los objetivos de negocio y la tolerancia al riesgo.
*   **Probador de Penetración (*Pentester* / Mi Foco):** Simula ataques del mundo real para identificar y explotar fallos de forma legal, ayudando a priorizar las mejoras técnicas antes de que un atacante real lo haga.
*   **Analista de Incidentes / SOC:** Monitoriza amenazas en tiempo real y ejecuta la contención de hackeos.

---

## 🛠️ 5. Arsenal Tecnológico Inicial

### Infraestructura de Defensa (Blue Team)
*   **Firewalls & IDS/IPS:** Barreras filtrantes y sistemas de monitorización para bloquear tráfico malicioso y anomalías en tiempo real.
*   **SIEM:** Centralizadores que recopilan, correlacionan y analizan eventos de seguridad de toda la red.

### Arsenal de Pruebas de Penetración (Red Team / Foco Web)
*   **Nmap:** Escaneo, mapeo de puertos y descubrimiento de activos en la red.
*   **Wireshark:** Análisis profundo de protocolos de red mediante la captura y rastreo de paquetes en tránsito.
*   **Metasploit:** Framework avanzado para la explotación activa de vulnerabilidades conocidas.
*   **Burp Suite:** Herramienta central para la intercepción de peticiones HTTP/S y pruebas de seguridad ofensiva en aplicaciones web.
*   **John the Ripper:** Descifrado y auditoría de la robustez de hashes de contraseñas.
