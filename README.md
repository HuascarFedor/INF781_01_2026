# Plan de Asignatura
## INF781 — Seguridad de Software

> **Marco referencial:** El programa docente del proceso enseñanza-aprendizaje está estructurado en correspondencia a los lineamientos del modelo académico; la asignatura orienta sus competencias hacia:
>
> - Desarrollo de aplicaciones seguras mediante buenas prácticas a lo largo del ciclo de vida del software: Comprensión de los fundamentos de seguridad (tríada CIA, OWASP Top 10), validación de entrada, manejo seguro de errores y configuración protegida del entorno.

---

## I. Identificación de la Asignatura

| Campo | Detalle |
|---|---|
| **Facultad** | Ciencias Puras |
| **Carrera** | Ingeniería Informática |
| **Asignatura** | Seguridad de Software |
| **Sigla y código** | INF 781 |
| **Pre-Requisito** | INF 663 |
| **Total horas** | 5 horas |
| **Trabajo independiente/semana** | 5 horas |
| **Número de créditos** | 5 |
| **Horas teóricas** | 2 |
| **Horas prácticas** | 0 |
| **Horas laboratorio** | 3 |
| **Semestre** | Séptimo Semestre (Mención Ingeniería de Software) |
| **Docente** | M. Sc. Huáscar Fedor Gonzales Guzmán |
| **Email** | huascar.fedor@gmail.com |

---

## II. Fundamentación y Justificación

Desde la perspectiva profesional, el mercado laboral demanda cada vez más perfiles de desarrollo con competencias en seguridad. La filosofía DevSecOps, adoptada por organizaciones líderes, integra la seguridad como responsabilidad compartida en todo el ciclo de desarrollo, haciendo que el conocimiento en seguridad de software sea una competencia transversal y no solo especializada.

Desde la perspectiva técnica, las vulnerabilidades de software son la causa principal de brechas de seguridad a nivel global. Informes anuales como el de Verizon Data Breach Investigations Report señalan consistentemente que la explotación de aplicaciones web representa uno de los vectores de ataque más frecuentes, con consecuencias que incluyen robo de datos, pérdidas económicas y daño reputacional.

Desde la perspectiva académica, la asignatura complementa y fortalece las competencias adquiridas en materias precedentes como Desarrollo Web Backend y Verificación y Validación de Software, añadiendo una dimensión de seguridad que convierte al estudiante en un desarrollador integral capaz de construir sistemas resilientes.

Desde la perspectiva social, la protección de los datos personales y la confianza digital son preocupaciones crecientes en la sociedad contemporánea. Formar profesionales con conciencia de seguridad contribuye directamente a la construcción de un ecosistema digital más seguro y confiable.

---

## III. Propósito

Formar al estudiante en la capacidad de construir software seguro por diseño, proporcionándole los conocimientos, técnicas y herramientas necesarias para identificar, prevenir y mitigar vulnerabilidades a lo largo de todo el ciclo de vida del desarrollo de software, integrando la seguridad como práctica continua dentro de entornos de desarrollo modernos.

---

## IV. Competencias de la Asignatura

### 4.1. Competencia Global

El estudiante desarrolla aplicaciones de software seguras aplicando buenas prácticas de protección a lo largo de todo el ciclo de vida del desarrollo, implementando mecanismos de autenticación, autorización, cifrado y prevención de vulnerabilidades, e integrando herramientas de análisis automatizado de seguridad en pipelines CI/CD.

### 4.2. Competencias Específicas

Al finalizar la asignatura, el estudiante será capaz de:

1. **Fundamentos y Desarrollo Seguro.** Configurar proyectos de software aplicando principios de diseño seguro, validación robusta de entrada, manejo seguro de errores y gestión protegida de variables de entorno.
2. **Autenticación y Autorización.** Implementar sistemas de autenticación y autorización utilizando hashing seguro de contraseñas, JSON Web Tokens con flujos completos, OAuth 2.0, RBAC y autenticación multifactor.
3. **Protección de Datos y Criptografía Práctica.** Aplicar técnicas criptográficas y mecanismos de protección para asegurar datos en reposo y en tránsito, configurar HTTPS/TLS, headers de seguridad, CORS restrictivo y rate limiting.
4. **Prevención de Vulnerabilidades en Código.** Identificar y prevenir las vulnerabilidades más comunes del OWASP Top 10 durante la escritura de código, aplicando consultas parametrizadas, sanitización de salida, tokens anti-CSRF, validación de archivos y logging seguro.
5. **Seguridad en el Ciclo CI/CD y Proyecto Integrador.** Integrar herramientas automatizadas de análisis de seguridad en pipelines de desarrollo continuo, incluyendo SAST, SCA, detección de secretos y escaneo de contenedores.

---

## V. Desarrollo de Saberes de la Asignatura

| Saber Conocer | Saber Hacer | Saber Ser |
|---|---|---|
| Comprende la tríada CIA, los principios de diseño seguro (mínimo privilegio, defensa en profundidad, fail-safe defaults) y el OWASP Top 10 como guía de prevención | Configura proyectos de software con estructura segura, validación robusta de entrada, manejo seguro de errores y gestión protegida de variables de entorno | Asume una actitud preventiva incorporando la seguridad como criterio fundamental desde las primeras líneas de código |
| Conoce los mecanismos de autenticación y autorización de la industria: hashing seguro, JWT, OAuth 2.0, OpenID Connect, RBAC y autenticación multifactor | Implementa flujos completos de autenticación con tokens, integración de login social con proveedores externos, control de acceso basado en roles y verificación de ownership sobre recursos | Reconoce la protección de credenciales e identidades de los usuarios como una responsabilidad ética del desarrollador |
| Comprende los fundamentos de criptografía aplicada: cifrado simétrico, HTTPS/TLS, headers de seguridad, gestión de secretos y mecanismos de protección contra abuso de servicios | Configura comunicaciones seguras, cifra datos sensibles a nivel de aplicación, implementa headers de seguridad HTTP, CORS restrictivo y rate limiting en APIs | Valora la protección de datos personales y la privacidad como un compromiso profesional y social |
| Identifica las vulnerabilidades más comunes en aplicaciones web y APIs: inyecciones SQL/NoSQL, XSS, CSRF, IDOR, upload inseguro de archivos y deficiencias en logging | Previene vulnerabilidades aplicando consultas parametrizadas, sanitización de salida, tokens anti-CSRF, UUIDs, validación de archivos por magic bytes y sistemas de logging que no expongan datos sensibles | Demuestra disciplina y rigor técnico al escribir código defensivo, evitando atajos que comprometan la seguridad |
| Conoce el enfoque DevSecOps y las herramientas de seguridad automatizada: SAST, SCA, detección de secretos, seguridad en contenedores y pipelines CI/CD seguros | Integra análisis estático de código, auditoría de dependencias, pre-commit hooks y escaneo de contenedores en pipelines de GitHub Actions, entregando proyectos con seguridad de extremo a extremo | Adopta la mejora continua de la seguridad como práctica inherente al ciclo de desarrollo, asumiendo que cada miembro del equipo es responsable de la calidad y protección del software |

---

## VI. Contenidos Temáticos de la Asignatura

### Unidad 1 — Fundamentos y Desarrollo Seguro

- 1.1 Tríada CIA y principios de diseño seguro: mínimo privilegio, defensa en profundidad, fail-safe defaults, separación de responsabilidades
- 1.2 OWASP Top 10 como guía de desarrollo: comprensión orientada a prevención, no solo detección
- 1.3 Validación y sanitización de entrada: whitelisting vs blacklisting, validación por tipo/longitud/rango, bibliotecas de validación (class-validator, Joi, Zod)
- 1.4 Manejo seguro de errores: evitar exposición de stack traces, mensajes genéricos al usuario, logging estructurado sin datos sensibles
- 1.5 Configuración segura del entorno: variables de entorno, archivos .env, separación de configuración por ambiente (dev/staging/prod), principio de no hardcodear secretos

### Unidad 2 — Autenticación y Autorización

- 2.1 Hashing de contraseñas: por qué no MD5/SHA1, implementación con bcrypt y Argon2, salt automático, costo computacional configurable
- 2.2 JSON Web Tokens (JWT): estructura (header.payload.signature), algoritmos de firma (HS256, RS256), expiración, refresh tokens; errores comunes: almacenamiento en localStorage, tokens sin expiración
- 2.3 Flujos de autenticación: registro seguro, login, logout (invalidación de tokens), reset de contraseña con tokens temporales
- 2.4 OAuth 2.0 y OpenID Connect: flujos (Authorization Code, PKCE para SPA/mobile), roles (Resource Owner, Client, Authorization Server, Resource Server); integración con proveedores externos
- 2.5 Autorización basada en roles y permisos: RBAC (Role-Based Access Control), guards/middleware de autorización, decoradores de roles; control de acceso a nivel de recurso
- 2.6 Multi-Factor Authentication (MFA): TOTP (Google Authenticator), implementación con bibliotecas como speakeasy/otplib

### Unidad 3 — Protección de Datos y Criptografía Práctica

- 3.1 HTTPS y TLS: por qué es obligatorio, certificados con Let's Encrypt, configuración en Nginx/servidor, redirección HTTP→HTTPS; headers de seguridad: HSTS, X-Frame-Options, X-Content-Type-Options, CSP
- 3.2 Cifrado de datos sensibles en base de datos: cifrado a nivel de campo (AES-256-GCM), cuándo cifrar vs cuándo hashear, cifrado transparente (TDE) vs a nivel de aplicación
- 3.3 Gestión de secretos: dotenv seguro, secret managers (HashiCorp Vault, AWS Secrets Manager conceptual), rotación de claves, nunca en repositorios (.gitignore, .gitattributes)
- 3.4 Comunicación segura entre servicios: API keys, mutual TLS (mTLS conceptual), firmado de requests (HMAC), rate limiting y throttling
- 3.5 Protección de datos personales: principios de minimización de datos, anonimización y pseudonimización, cumplimiento básico de GDPR/normativas de protección de datos
- 3.6 CORS (Cross-Origin Resource Sharing): configuración correcta, whitelist de orígenes, preflight requests, errores comunes de configuración permisiva

### Unidad 4 — Prevención de Vulnerabilidades en Código

- 4.1 Inyección SQL y NoSQL: cómo ocurre, consultas parametrizadas, uso correcto de ORM (TypeORM, Prisma, SQLAlchemy), prevención en consultas raw
- 4.2 Cross-Site Scripting (XSS): tipos (reflejado, almacenado, DOM), sanitización de salida, escape por contexto (HTML, JS, URL), Content Security Policy como defensa en profundidad
- 4.3 Cross-Site Request Forgery (CSRF): cómo funciona, tokens anti-CSRF, atributo SameSite en cookies, patrón de double-submit cookie
- 4.4 Insecure Direct Object References (IDOR): validación de ownership, no exponer IDs secuenciales (uso de UUID), middleware de verificación de acceso a recursos
- 4.5 Upload seguro de archivos: validación de tipo MIME real (magic bytes), límites de tamaño, almacenamiento fuera del webroot, renombrado de archivos, escaneo antivirus básico
- 4.6 Logging y monitoreo de seguridad: qué registrar (intentos fallidos, accesos a recursos sensibles), qué nunca registrar (contraseñas, tokens, datos personales), alertas y correlación de eventos

### Unidad 5 — Seguridad en el Ciclo CI/CD y Proyecto Integrador

- 5.1 Análisis estático de código (SAST): SonarQube, Semgrep o ESLint con plugins de seguridad; detección de vulnerabilidades antes de ejecutar
- 5.2 Auditoría de dependencias (SCA): npm audit, pip-audit, Snyk; gestión de vulnerabilidades en paquetes de terceros, lock files, actualizaciones automatizadas
- 5.3 Pre-commit hooks de seguridad: git-secrets, detect-secrets, linters de seguridad antes de cada commit
- 5.4 Pipeline CI/CD seguro: integración de SAST + SCA en GitHub Actions o GitLab CI, fail on critical vulnerabilities, reportes automáticos
- 5.5 Seguridad en contenedores: buenas prácticas en Dockerfile (usuario no-root, imágenes mínimas, multi-stage builds), escaneo de imágenes con Trivy

---

## VII. Métodos y Estrategias de Enseñanza-Aprendizaje

Se utilizan métodos y estrategias de enseñanza y aprendizaje de acuerdo con el avance de la ciencia y la tecnología educativa:

- Explicativo ilustrativo
- Aprendizaje participativo
- Método problémico
- Método expositivo
- Simulación de casos
- Método investigativo
- Lluvia de ideas
- Aprendizaje por Proyectos

### Recursos

**Aula:**
- Computadora
- Data display
- Pizarra
- Guías de laboratorio
- Internet
- Plataforma de aprendizaje en línea, oficial de la UATF
- Herramienta de comunicación virtual sincrónica (Zoom, Meet, Webex u otro)

**Laboratorio:**
- Node.js
- Visual Studio Code
- GitHub
- PostgreSQL
- OWASP Juice Shop
- Burp Suite Community Edition
- Postman
- Curl
- Semgrep
- ESLint (eslint-plugin-security)
- SonarQube Community Edition
- npm Audit
- Snyk CLI
- GitHub Actions
- detect-secrets
- Docker
- Trivy
- Winston
- Kali Linux

---

## VIII. Sistema de Evaluación

Las asignaturas de laboratorio se evalúan de la siguiente manera:

| Componente | Porcentaje |
|---|---|
| Exámenes Parciales | 40% |
| Prácticas | 10% |
| Laboratorio | 20% |
| Examen Final | 30% |
| **Total** | **100%** |

### Tipos de Evaluación

| Tipo | Técnica | Instrumento | Evidencia | Entorno |
|---|---|---|---|---|
| Diagnóstica | Interrogatorio (presencial y/o virtual) | Guía de observación | Cuestionario resuelto | Aula (presencial y/o virtual) |
| Formativa | Desempeño (presencial y/o virtual) | Prueba de laboratorio | Presentación, exposición | Aula (presencial y/o virtual) |
| Sumativa / Producto | Enunciado, ejercicios (presencial y/o virtual) | Prueba de laboratorio | Presentación de trabajo final | Aula (presencial y/o virtual) |

---

## IX. Bibliografía

- Hoffman, A. (2024). *Web Application Security: Exploitation and Countermeasures for Modern Web Applications* (2a ed.). O'Reilly Media.
- Janca, T. (2020). *Alice and Bob Learn Application Security*. Wiley.
- Richer, J. & Sanso, A. (2017). *OAuth 2 in Action*. Manning Publications.
- Ahmad Khan, S. & Kumar, R. (2023). *Software Security: Concepts & Practices*. Chapman and Hall/CRC.
- OWASP Foundation. (2021). *OWASP Top 10:2021*. https://owasp.org/Top10/
- Stuttard, D. & Pinto, M. (2011). *The Web Application Hacker's Handbook: Finding and Exploiting Security Flaws* (2a ed.). Wiley.
- Shostack, A. (2014). *Threat Modeling: Designing for Security*. Wiley.
- McDonald, M. (2020). *Web Security for Developers: Real Threats, Practical Defense*. No Starch Press.
- Ball, C. J. (2022). *Hacking APIs: Breaking Web Application Programming Interfaces*. No Starch Press.
- Kim, P., Bhatt, H. & Muniz, J. (2021). *The DevSecOps Playbook: Deliver Continuous Security at Speed*. Wiley.

---

## X. Cronograma

*(Ver documento oficial de la asignatura para el cronograma detallado por semana.)*
