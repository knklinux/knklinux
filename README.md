# 👋 Hola, soy Arkaitz (knklinux)

**Cybersecurity Analyst & Junior Pentester en formación** · Autodidacta · Linux · Red Team

Aprendo ciberseguridad **construyendo mis propias herramientas** y documentando cada hallazgo. Sin título universitario, pero con un portfolio real de proyectos open-source que lo demuestran.

[![Linux](https://img.shields.io/badge/OS-Linux-9cf)](#)
[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](#)
[![Bash](https://img.shields.io/badge/CLI-Bash-4e9a06)](#)
[![Pentest](https://img.shields.io/badge/foco-Pentesting-ff8800)](#)
[![SOC](https://img.shields.io/badge/foco-Análisis%20SOC-33ff66)](#)
[![MITRE](https://img.shields.io/badge/MITRE%20ATT%26CK-ATT%26CK-red)](#)

---

## 🚀 Proyectos

| Proyecto | Descripción |
|----------|-------------|
| **[CYBERGRAD](https://github.com/knklinux/cybergrad)** 🎮 | Simulador de carrera SOC + Red Team jugable online, construido como proyecto de aprendizaje: 6 casos blue team (phishing, BEC, ransomware, fuerza bruta, exfiltración DNS…) y 6 pentests ofensivos (nmap, hydra, sqlmap, Metasploit, Mimikatz) con progresión de analista junior a CISO y lecciones **MITRE ATT&CK**. **[Juega online](https://knklinux.github.io/cybergrad/)**. |
| **[Aion Sincro](https://github.com/knklinux/aion-sincro)** ⭐ | Asistente de IA open-source para pentesting y red team: 5 motores de IA gratuitos, informes profesionales (Markdown/PDF/Word), auditoría ISO 27001:2022, ruta guiada de red team con examen y certificación, cifrado WebCrypto y suite de seguridad con ~995 tests + pruebas de mutación. |
| **[CERTO](https://github.com/knklinux/certo-demo)** 🏢 | Plataforma de auditoría de cumplimiento normativo multi-estándar: 10 normas (ISO 27001, 9001, 14001, ENS, RGPD…) con 192 controles, informes profesionales con hash SHA-256 de autenticidad y certificados verificables. [Demo en vivo](https://knklinux.github.io/certo-demo/). Proyecto comercial (consultoría ISO) — la vitrina pública es open-source. |
| **[CyberGuard](https://github.com/knklinux/ciberguard)** 🛡️ | Toolkit CLI modular de seguridad en Python, cero dependencias: módulo ofensivo (nmap + searchsploit) y auditor de hardening (sysctl + sshd_config) con salida CI/CD-friendly. |

> 🔭 Buscando mi **primera oportunidad** en ciberseguridad: junior pentester, analista de seguridad o SOC. Disponible para remoto.

---

## 📋 Caso de estudio: CYBERGRAD — ciberseguridad aprendida construyendo

CYBERGRAD es un **simulador de carrera SOC + Red Team** que empecé como proyecto de aprendizaje autodidacta (con ayuda de agentes de IA para el código, validando cada entrega con tests y CI). Para construirlo tuve que entender —y saber explicar— los ataques que simula: es mi forma de demostrar que lo que aprendo, lo aplico.

### 🎯 Lo que demuestra para pentesting y análisis SOC

- **Metodología ofensiva real**: la campaña red team sigue el ciclo completo de un pentest — contrato → reconocimiento (`nmap`, `gobuster`, `nikto`) → acceso (`hydra`, `sqlmap`, `Metasploit`) → escalada y post-explotación (`Mimikatz`) → exfiltración → **informe ejecutivo**. Modelarlo con fidelidad exige entender cada fase y cada herramienta.
- **Respuesta a incidentes**: la campaña SOC entrena triaje, lectura de indicadores (IOCs), phishing, BEC, ransomware, fuerza bruta y exfiltración por túnel DNS — el trabajo real de un analista de nivel 1 y 2.
- **Estándares**: cada caso está mapeado a **MITRE ATT&CK**, y los informes se evalúan con **calificaciones objetivas (S+ a C)** según cobertura de indicadores, tiempo y errores — evaluar con criterio, no a ojo.
- **Rigor de seguridad**: auditando el proyecto encontré y **purgué del historial git una ruta local del equipo filtrada** (blobs y mensajes de commit) con `filter-branch` + force-push, verificando el resultado en la API de GitHub. El juego va con **CI en verde en cada push** (sintaxis, lint y smoke test E2E).

### 📊 Métricas (todo en producción y verificado)

| Métrica | Valor |
|---------|-------|
| Casos de incidentes blue team (SOC) | **6** — phishing, BEC, falso positivo, ransomware, fuerza bruta, exfiltración por túnel DNS |
| Pentests red team | **6** — nmap/gobuster, hydra, sqlmap, Metasploit, Mimikatz, exfiltración |
| Campañas jugables | **2** (blue team + red team) con progresión a CISO |
| Prácticas guiadas de becario | **4** — paso a paso explicando el *porqué* de cada decisión |
| Lecciones MITRE ATT&CK | 1 por caso, mapeando TTPs del ataque |
| Logros e insignias | **17** — por rango, hitos y 1 huevo de pascua oculto |
| Calidad | CI en verde: `node --check` (31 archivos), ESLint 0 errores, smoke test E2E con Playwright (cero errores de consola) |
| Despliegue | GitHub Pages · sin backend · sin dependencias |

### 🧠 Por qué me prepara para el puesto

- **Pensamiento analítico**: cada caso es un ejercicio de investigación — leer evidencias, correlacionar indicadores y decidir bajo presión de SLA.
- **Herramientas**: nmap, gobuster, nikto, hydra, sqlmap, Metasploit, Mimikatz — las mismas que uso en OverTheWire, TryHackMe y HackTheBox.
- **Documentación profesional**: informes de incidente y de pentest ejecutivos, exportables (Markdown/JSON), con ratings y lecciones aprendidas.
- **Cultura de calidad**: tests, CI, auditoría de seguridad e historial limpio — no solo "código que funciona en mi máquina".

> 🔗 **Pruébalo tú mismo:** https://knklinux.github.io/cybergrad/ · Código: https://github.com/knklinux/cybergrad

---

## 📈 Progreso y laboratorios

* **OverTheWire (Bandit):** nivel 27 alcanzado — administración Linux CLI, filtrado de texto, permisos y criptografía básica.
* **TryHackMe:** rutas de *SOC Analyst Tier 1* y *Pre-Security*.
* **HackTheBox:** criptografía y máquinas Linux básicas.

---

## 🛠️ Tech stack

* **Sistemas:** Linux (KDE Neon, Linux Mint, Kali Linux).
* **CLI y scripting:** Bash, Python, `find`, `grep`, `netcat`, `openssl`, `ssh`.
* **Redes:** análisis de tráfico, direccionamiento, TCP/IP.
* **Seguridad ofensiva:** nmap, gobuster, nikto, hydra, sqlmap, Metasploit, Mimikatz, Burp Suite, OSINT.
* **Seguridad defensiva:** triaje de incidentes, IOCs, MITRE ATT&CK, hardening (sysctl, sshd), OWASP Top 10, ISO 27001.

---

## 🎯 En camino

* **eJPT** (eLearnSecurity Junior Penetration Tester) — en preparación.
* Seguir construyendo herramientas open-source que demuestren con código lo que aprendo.

---

## 📬 Contacto

* GitHub: [knklinux](https://github.com/knklinux)
* Buscando mi primera oportunidad: junior pentester, analista de seguridad o SOC — disponible para remoto.

---

*Perfil en constante evolución — igual que yo. Aprendizaje continuo, práctica real y código abierto.*
