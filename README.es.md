🌍 [English](README.md) | [Türkçe](README.tr.md) | [Español](README.es.md)

# 🤖 Codex CLI — Guía General de Usuario

> **El agente de codificación de IA basado en terminal desarrollado por OpenAI que se ejecuta en su shell local.**

<div align="center">

![Versión](https://img.shields.io/badge/version-latest-blue)
![Licencia](https://img.shields.io/badge/license-Proprietary-red)

</div>

---

## 📚 Tabla de Contenidos

- [¿Qué es Codex CLI?](#qué-es-codex-cli)
- [Instalación](#instalación)
- [Inicio Rápido](#inicio-rápido)
- [Modo Interactivo (TUI)](#modo-interactivo-tui)
- [Configuración](#configuración)
- [Comandos de Barra Diagonal](#comandos-de-barra-diagonal)
- [Atajos de Teclado Esenciales](#atajos-de-teclado-esenciales)
- [Consejos y Trucos](#consejos-y-trucos)
- [Recursos](#recursos)
- [Tarjeta de Referencia Rápida](#tarjeta-de-referencia-rápida)

---

## ¿Qué es Codex CLI?

**Codex CLI** es un agente de codificación basado en terminal desarrollado por OpenAI que ayuda a escribir, editar y ejecutar código directamente desde la línea de comandos.

---

## Instalación

### 🪟 Windows (WinGet)
```powershell
winget install OpenAI.Codex
```

### Instalación Global (npm)
```bash
npm install -g @openai/codex
```

### 🍎 macOS / 🐧 Linux (Install Script)
```bash
curl -fsSL https://chatgpt.com/codex/install.sh | sh
```

---

## Tarjeta de Referencia Rápida

```
┌──────────────────────────────────────────────────────────┐
│                 🤖 Referencia Rápida Codex               │
├──────────────────────────────────────────────────────────┤
│                                                          │
│  INICIAR                   GESTIONAR                     │
│  codex           .......  Iniciar TUI     /new           │
│  codex "prompt"  .......  Con prompt      /clear         │
│                                           /quit          │
│                                                          │
│  EDITOR                    ATAJOS                        │
│  @archivo        .......  Ref. archivo    Ctrl+C         │
│  !comando        .......  Ejecutar shell  Ctrl+D         │
│  Shift+Enter     .......  Nueva línea     Ctrl+O         │
│                                           Ctrl+L         │
│                                                          │
│  CONFIG                    CONTEXTO                      │
│  /config         .......  Panel de Ajustes /ide          │
│  /model          .......  Cambiar modelo  /status        │
│  /permissions    .......  Seguridad       /agent         │
│  /approve        .......  Auto aprobación /vim           │
│                                                          │
└──────────────────────────────────────────────────────────┘
```
