<div align="center">

# Dmitry Popov

### Reverse Engineer • Embedded Security Researcher • Systems Engineer

**Android Internals · Embedded Platforms · Automotive Security · Secure Software Delivery**

[![Email](https://img.shields.io/badge/Email-deymonster%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:deymonster@gmail.com)
[![Telegram](https://img.shields.io/badge/Telegram-@Deymonster-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Deymonster)
[![Profile views](https://komarev.com/ghpvc/?username=deymonster&style=for-the-badge&color=6C63FF)](https://github.com/deymonster)

</div>

---

## About Me

I am a Reverse Engineer and Embedded Security Researcher focused on understanding how complex systems actually work.

My work combines reverse engineering, Android internals, dynamic instrumentation, embedded platforms and secure software delivery. I spend most of my time analyzing proprietary systems, recovering undocumented functionality, studying operating system internals and building production-grade infrastructure around them.

In recent years I have focused on Android/QNX automotive platforms, OTA update systems, telematics infrastructure, Android boot internals, runtime modification technologies and secure deployment pipelines.

```text
Reverse Engineering
        ↓
Platform Internals
        ↓
Security Research
        ↓
Secure System Design
```

## Areas of Expertise

* Reverse Engineering
* Android Internals
* Embedded Systems
* Automotive Platforms
* Dynamic Instrumentation
* OTA Systems
* Protocol Analysis
* Runtime Modification
* Secure Software Delivery

## Selected Research & Engineering Projects

<table>
<tr>
<td width="50%" valign="top">

### Android/QNX Automotive Platform Research

Reverse engineering of an Android/QNX-based automotive infotainment platform powered by Qualcomm Snapdragon 8155.

Research areas:

• Android boot process
• OTA update architecture
• System services
• Security mechanisms
• Platform internals

`Android` `QNX` `Qualcomm 8155` `OTA` `Embedded Systems`

</td>

<td width="50%" valign="top">

### Runtime Localization Framework

Designed a Magisk-based runtime translation framework capable of localizing proprietary Android applications without modifying original APK files.

Features:

• Runtime resource replacement
• JSON-based dictionaries
• OTA-delivered translations
• Non-invasive deployment

`Magisk` `Android Internals` `Runtime Hooking`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### Telematics Protocol Reverse Engineering

Analysis of proprietary T-Box communication protocols and mobile application traffic.

Achievements:

• HTTPS traffic interception
• SSL pinning bypass
• Protocol reconstruction
• Command reproduction

`Frida` `HTTP Toolkit` `Mobile Security` `Protocol Analysis`

</td>

<td width="50%" valign="top">

### Secure OTA Delivery Platform

Building a secure deployment pipeline for remote delivery of embedded software modules.

Stack:

• Rust agent
• NestJS GraphQL backend
• Next.js frontend
• MinIO object storage
• Automated OTA updates

`Rust` `mTLS` `GraphQL` `Secure Deployment`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### Android Init & Magisk Internals

Source-level investigation of Android initialization process, SELinux policy generation and Magisk internals.

Research topics:

• init process
• SEPolicy generation
• boot sequence
• module loading

`Android Init` `SELinux` `Magisk`

</td>

<td width="50%" valign="top">

### Dynamic Instrumentation & Binary Analysis

Static and runtime analysis of Android native binaries using Ghidra and Frida.

Activities:

• Function recovery
• Runtime tracing
• Hook development
• Behavior analysis

`Ghidra` `Frida` `Reverse Engineering`

</td>
</tr>
</table>

## Core technology stack

### Systems, security & platform

<p>
  <img src="https://img.shields.io/badge/Rust-111827?style=for-the-badge&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/QNX-111827?style=for-the-badge&logo=blackberry&logoColor=white" alt="QNX" />
  <img src="https://img.shields.io/badge/Android_Internals-111827?style=for-the-badge&logo=android&logoColor=3DDC84" alt="Android Internals" />
  <img src="https://img.shields.io/badge/Frida-111827?style=for-the-badge&logoColor=white" alt="Frida" />
  <img src="https://img.shields.io/badge/Linux-111827?style=for-the-badge&logo=linux&logoColor=FCC624" alt="Linux" />
</p>

### Backend & API engineering

<p>
  <img src="https://img.shields.io/badge/NestJS-111827?style=for-the-badge&logo=nestjs&logoColor=E0234E" alt="NestJS" />
  <img src="https://img.shields.io/badge/GraphQL-111827?style=for-the-badge&logo=graphql&logoColor=E10098" alt="GraphQL" />
  <img src="https://img.shields.io/badge/TypeScript-111827?style=for-the-badge&logo=typescript&logoColor=3178C6" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Python-111827?style=for-the-badge&logo=python&logoColor=3776AB" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-111827?style=for-the-badge&logo=fastapi&logoColor=009688" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Django-111827?style=for-the-badge&logo=django&logoColor=44B78B" alt="Django" />
</p>

### Frontend, data & infrastructure

<p>
  <img src="https://img.shields.io/badge/Next.js-111827?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/React-111827?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/PostgreSQL-111827?style=for-the-badge&logo=postgresql&logoColor=4169E1" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Docker-111827?style=for-the-badge&logo=docker&logoColor=2496ED" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub_Actions-111827?style=for-the-badge&logo=githubactions&logoColor=2088FF" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Prometheus-111827?style=for-the-badge&logo=prometheus&logoColor=E6522C" alt="Prometheus" />
</p>

## How I approach engineering

| Principle | What it means in practice |
|:--|:--|
| **Security by design** | Threat-aware architecture, least privilege, artifact integrity, and controlled deployment paths. |
| **Understand the internals** | Source-level and runtime investigation instead of treating platforms as black boxes. |
| **Type-safe architecture** | Explicit contracts across Rust, TypeScript, NestJS, GraphQL, and Next.js applications. |
| **Production readiness** | Automation, observability, predictable releases, and maintainable operational workflows. |
| **End-to-end ownership** | Connecting low-level platform behavior with backend services and polished user-facing products. |

## GitHub activity

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=deymonster&show_icons=true&theme=transparent&hide_border=true&title_color=6C63FF&icon_color=6C63FF&text_color=8B949E&include_all_commits=true&count_private=true" alt="Dmitry's GitHub statistics" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=deymonster&layout=compact&theme=transparent&hide_border=true&title_color=6C63FF&text_color=8B949E&langs_count=8" alt="Most used languages" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=deymonster&bg_color=00000000&color=8B949E&line=6C63FF&point=6C63FF&area=true&area_color=6C63FF&hide_border=true" alt="Dmitry's contribution graph" />
</div>

---

<div align="center">

### Let's build reliable and secure systems

I am open to engineering collaborations involving **platform security**, **embedded systems**, **backend architecture**, and **full-stack product development**.

[![Email me](https://img.shields.io/badge/Email_me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:deymonster@gmail.com)
[![Message on Telegram](https://img.shields.io/badge/Message_on_Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Deymonster)

</div>
