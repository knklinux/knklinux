# 👋 Hola, soy Arkaitz (knklinux)

**Cybersecurity Analyst & Junior Pentester en formación** · Autodidacta · Linux · Red Team

Aprendo ciberseguridad **construyendo mis propias herramientas** y documentando cada hallazgo. Sin título universitario, pero con un portfolio real de proyectos open-source que lo demuestran.

[![Linux](https://img.shields.io/badge/OS-Linux-9cf)](#)
[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](#)
[![Bash](https://img.shields.io/badge/CLI-Bash-4e9a06)](#)
[![Pentest](https://img.shields.io/badge/foco-Pentesting-ff8800)](#)

---

## 🚀 Proyectos destacados

[![CYBERGRAD — Simulador de carrera SOC](https://knklinux.github.io/cybergrad/assets/cover.jpg)](https://knklinux.github.io/cybergrad/)

| Proyecto | Descripción |
|----------|-------------|
| **[CYBERGRAD](https://github.com/knklinux/cybergrad)** 🎮 | Simulador de carrera SOC tipo videojuego, jugable online: 6 casos blue team (phishing, BEC, ransomware, fuerza bruta, exfiltración DNS…) + campaña red team de 6 pentests (nmap, hydra, sqlmap, Metasploit, Mimikatz), modo becario guiado paso a paso, progresión de analista junior a CISO y lecciones MITRE ATT&CK — con Jimmy, tu director de SOC sintético. **[Juega online](https://knklinux.github.io/cybergrad/)**. |
| **[Aion Sincro](https://github.com/knklinux/aion-sincro)** ⭐ | Asistente de IA open-source, compañera de aprendizaje de pentesting y red team. 5 motores de IA gratuitos, voz (Piper local + Mistral Voxtral), informes profesionales (Markdown/PDF/Word), auditoría ISO 27001:2022, ruta guiada de red team con examen y certificación, cifrado WebCrypto y suite de seguridad con ~995 tests + pruebas de mutación. |
| **[CERTO](https://github.com/knklinux/certo-demo)** 🏢 | Plataforma de auditoría de cumplimiento normativo multi-estándar: 10 normas (ISO 27001, 9001, 14001, ENS, RGPD…) con 192 controles, informes profesionales con hash SHA-256 de autenticidad y certificados verificables. [Demo en vivo](https://knklinux.github.io/certo-demo/). Proyecto comercial (consultoría ISO) — la vitrina pública es open-source. |
| **[CyberGuard](https://github.com/knklinux/ciberguard)** | Toolkit CLI modular de seguridad en Python, cero dependencias: módulo ofensivo (nmap + searchsploit) y auditor de hardening (sysctl + sshd_config) con salida CI/CD-friendly. |

> 🔭 Buscando mi **primera oportunidad** en ciberseguridad: junior pentester, analista de seguridad o SOC. Disponible para remoto.

---

## 📋 Caso de estudio: CYBERGRAD — dirigiendo un producto completo con agentes de IA

**CYBERGRAD no es solo un juego: es mi demostración de cómo se trabaja con agentes de IA para construir producto de principio a fin.** Lo especifiqué, dirigí y validé sesión a sesión junto a un agente de programación, hasta dejarlo con calidad de producción. Es la pieza que mejor explica por qué encajo en roles de entrenamiento y dirección de IA, además de ciberseguridad.

### 🎯 Mi rol: director de producto + evaluador

No escribí cada línea: **especifiqué, revisé, rompí y redirigí**. El patrón de trabajo fue el de un *AI trainer / prompt engineer* en producción:

1. **Especificar con visión** — *"un simulador de carrera SOC tipo videojuego, con terminales funcionales, se empieza de analista junior y se escala, 100% fiel a un entorno real"* → de esa frase salió un producto completo de 2 campañas.
2. **Iterar con criterio** — cada mejora fue incremental y con propósito: SEO para el portfolio, campaña red team, modo becario para quien no ha tocado un SOC, guardado, logros, estadísticas, exportación, CI… 22 entregas en el historial, cada una verificada en navegador antes de publicar.
3. **Exigir calidad y seguridad** — pedí auditorías de fugas en código y repo: encontré y **purgué del historial git una ruta local del equipo filtrada** (presente en blobs y mensajes de commit) con `filter-branch` + force-push, verificando el resultado en la API de GitHub.
4. **Pensar en el usuario final** — tutorial para novatos absolutos, modo laboratorio para equivocarse sin penalización, botón de compartir, tarjeta Open Graph bonita para LinkedIn y hasta un huevo de pascua.

### 📊 Métricas (todo en producción y verificado)

| Métrica | Valor |
|---------|-------|
| Casos de incidentes blue team (SOC) | **6** — phishing, BEC, falso positivo, ransomware, fuerza bruta, exfiltración por túnel DNS |
| Pentests red team | **6** — nmap/gobuster, hydra, sqlmap, Metasploit, Mimikatz, exfiltración |
| Campañas jugables | **2** (blue team + red team) con progresión a CISO |
| Prácticas guiadas de becario | **4** — paso a paso explicando el *porqué* de cada decisión |
| Logros e insignias | **17** — por rango, hitos y 1 huevo de pascua oculto |
| Persistencia | **2 ranuras de guardado** + reinicio selectivo por campaña |
| Estadísticas por partida | tiempo jugado, acciones OK/errores, pistas, ratings por caso, barras de XP |
| Exportación | informe de carrera en **Markdown y JSON**, copia al portapapeles, botón **LinkedIn** |
| Calidad | **CI en verde en cada push**: `node --check` (31 archivos), ESLint 0 errores, smoke test E2E con Playwright (carga → onboarding → caso → terminal, cero errores de consola) |
| Despliegue | GitHub Pages · sin backend · sin dependencias |

### 🧠 Qué demuestra para un rol de entrenador de IA

- **Saber dirigir agentes**: convertir una visión en especificaciones accionables y mantener el rumbo durante 20+ iteraciones sin perder el objetivo.
- **Saber evaluar salida**: revisar cada cambio y detectar errores reales — encontré un bug de parseo (`de` por `of`) en el motor de logros, una filtración de datos en el historial git y un CSS que rompía el banner ASCII — y hacer que se corrigieran con verificación.
- **Saber iterar con el usuario en mente**: decidir qué construir, cuándo parar de añadir features y cómo hacer que un principiante aprenda sin frustrarse.
- **Cultura de calidad**: CI, tests E2E, auditoría de seguridad, historial limpio y documentación — no solo "código que funciona en mi máquina".

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
* **Seguridad:** nmap, gobuster, Burp Suite, OSINT, OWASP Top 10, ISO 27001.

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
