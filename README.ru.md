<h1 align="center">🛠️ Lizerium.Tools.Structs 🛠️</h1>

<p align="center">
  Структурная карта инженерных инструментов, исследовательских утилит и вспомогательных программ экосистемы Lizerium
</p>

<div align="center" style="margin: 20px 0; padding: 10px; background: #1c1917; border-radius: 10px;">
  <strong>🌐 Язык: </strong>
  
  <span style="color: #F5F752; margin: 0 10px;">
    ✅ 🇷🇺 Русский (текущий)
  </span>
  | 
  <a href="./README.md" style="color: #0891b2; margin: 0 10px;">
    🇺🇸 English
  </a>
</div>

---

> [!NOTE]
> Этот проект является частью экосистемы **Lizerium** и относится к направлению:
>
> - [`Lizerium.Hub`](https://github.com/Lizerium/Lizerium.Hub)
>
> Если вы ищете связанные инженерные и вспомогательные инструменты, начните оттуда.

## Назначение

Этот репозиторий является **структурным индексом инженерного и инструментального слоя** внутри экосистемы **Lizerium**.

Он не является основной реализацией, а служит как:

- карта вспомогательных программных инструментов
- точка навигации по инженерному tooling-слою
- описание ролей служебных и исследовательских репозиториев
- место для логической классификации утилит и технических решений
- слой архитектурного обзора инструментального контура экосистемы

---

## Роль в экосистеме

Этот репозиторий помогает понять:

- какие проекты относятся к инструментальному и инженерному слою Lizerium
- как разделены редакторы, исследовательские утилиты, анализаторы и служебные приложения
- где находятся точки входа в технические рабочие процессы
- как устроена логика вспомогательных инструментов
- какие компоненты используются для анализа, конвертации, проверки, сопровождения и инженерной поддержки экосистемы

---

## Что входит в это направление

### 1. 📦 Data и format tooling

Инструменты для чтения, анализа, преобразования, сериализации и сопровождения игровых данных и форматов.

- [`LizeriumDataToolkit`](https://github.com/Lizerium/LizeriumDataToolkit)
- [`FLResourceLibrary`](https://github.com/Lizerium/FLResourceLibrary)
- [`LizeriumUTFtoXML`](https://github.com/Lizerium/LizeriumUTFtoXML)

---

### 2. 🧪 Анализ, аудит и исследование

Инженерные и исследовательские утилиты, применяемые для проверки, диагностики, аудита и анализа систем.

- [`FreelancerAdminAudit`](https://github.com/Lizerium/FreelancerAdminAudit)
- [`KnowledgeBase`](https://github.com/Lizerium/KnowledgeBase)

---

### 3. 🖍️ Редакторы и рабочие UI-инструменты

Программы и интерфейсы, упрощающие работу с данными, контентом и внутренними форматами.

- [`CompilerInfocardsUI`](https://github.com/Lizerium/CompilerInfocardsUI)
- [`LizeriumVSCodeColorPicker`](https://github.com/Lizerium/LizeriumVSCodeColorPicker)

---

### 4. 🔄 Подготовка релизов и техническое сопровождение

Вспомогательные инструменты, используемые в инженерных и release-сценариях.

- [`LizeriumFindChanges`](https://github.com/Lizerium/LizeriumFindChanges)

---

## Архитектурная схема

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
