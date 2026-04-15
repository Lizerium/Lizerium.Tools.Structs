<h1 align="center">🛠️ Lizerium.Tools.Structs 🛠️</h1>

<p align="center">
  Structural map of engineering tools, research utilities, and support applications within the Lizerium ecosystem
</p>

<div align="center" style="margin: 20px 0; padding: 10px; background: #1c1917; border-radius: 10px;">
  <strong>🌐 Language: </strong>
  
  <a href="./README.ru.md" style="color: #F5F752; margin: 0 10px;">
    🇷🇺 Russian
  </a>
  | 
  <span style="color: #0891b2; margin: 0 10px;">
    ✅ 🇺🇸 English (current)
  </span>
</div>

---

> [!NOTE]
> This project is part of the **Lizerium** ecosystem and belongs to the following direction:
>
> - [`Lizerium.Hub`](https://github.com/Lizerium/Lizerium.Hub)
>
> If you are looking for related engineering and supporting tools, start there.

## Purpose

This repository serves as a **structural index of the engineering and tooling layer** within the **Lizerium** ecosystem.

It is not a primary implementation, but acts as:

- a map of supporting software tools
- a navigation entry point into the engineering tooling layer
- a description of roles for utility and research repositories
- a place for logical classification of tools and technical solutions
- an architectural overview layer of the ecosystem’s tooling domain

---

## Role in the Ecosystem

This repository helps to understand:

- which projects belong to the tooling and engineering layer of Lizerium
- how editors, research utilities, analyzers, and support applications are separated
- where the entry points into technical workflows are located
- how the logic of supporting tools is structured
- which components are used for analysis, conversion, validation, maintenance, and engineering support across the ecosystem

---

## What’s Included in This Direction

### 1. 📦 Data & Format Tooling

Tools for reading, analyzing, transforming, serializing, and maintaining game data and formats.

- [`LizeriumDataToolkit`](https://github.com/Lizerium/LizeriumDataToolkit)
- [`FLResourceLibrary`](https://github.com/Lizerium/FLResourceLibrary)
- [`LizeriumUTFtoXML`](https://github.com/Lizerium/LizeriumUTFtoXML)

---

### 2. 🧪 Analysis, Audit & Research

Engineering and research utilities used for validation, diagnostics, auditing, and system analysis.

- [`FreelancerAdminAudit`](https://github.com/Lizerium/FreelancerAdminAudit)
- [`KnowledgeBase`](https://github.com/Lizerium/KnowledgeBase)

---

### 3. 🖍️ Editors & UI Tools

Applications and interfaces that simplify working with data, content, and internal formats.

- [`CompilerInfocardsUI`](https://github.com/Lizerium/CompilerInfocardsUI)
- [`LizeriumVSCodeColorPicker`](https://github.com/Lizerium/LizeriumVSCodeColorPicker)

---

### 4. 🔄 Release Preparation & Technical Support

Supporting tools used in engineering workflows and release scenarios.

- [`LizeriumFindChanges`](https://github.com/Lizerium/LizeriumFindChanges)

---

## Architecture Diagram

```text
Lizerium.Tools.Structs
├── Data Tooling
│   ├── LizeriumDataToolkit
│   └── FLResourceLibrary
│
├── Research & Audit
│   ├── FreelancerAdminAudit
│   └── KnowledgeBase
│
├── Editors & UI Tools
│   ├── CompilerInfocardsUI
│   └── LizeriumVSCodeColorPicker
│
└── Release Support
    └── LizeriumFindChanges
```
