# 📄 Project Charter – Alphalang

---

## 1. Project Objectives

**Purpose**  
To create a **simple**, **multilingual programming language** designed to help beginners learn programming by allowing them to write code in their native language.

**SMART Objectives**

- **Specific**: Build an educational programming language focused on simplicity and multilingual syntax to ease access for global beginners.
- **Measurable**: Deliver an alpha version supporting 2 languages (English, French), plus 5 beginner-friendly tutorials.
- **Achievable**: Keep the feature set minimal — focusing on core concepts like variables, conditionals, loops, and functions — to allow rapid development and testing.
- **Relevant**: The language addresses the real barrier many beginners face: learning programming in a foreign language. This enhances accessibility and inclusion.
- **Time-bound**: Release the alpha version and publish the tutorials and documentation by **July 18, 2025**.

---

## 2. Stakeholders and Roles

| Stakeholder              | Role / Description                                                   |
|--------------------------|----------------------------------------------------------------------|
| Project Creator (You)    | Project lead, main developer                                         |
| Beginners                | End users, educational target audience                               |
| Teachers / Educators     | Provide feedback on clarity and educational value                    |
| Volunteer Translators    | Translate syntax and messages                                        |
| GitHub Contributors      | Help with code, documentation, and testing                           |

---

## 3. Scope

**In Scope**
- Interpreter with support for language basics (expressions, conditions, loops, functions)
- Syntax translation system (internationalization)
- Online tutorials and documentation
- Command-line interface

**Out of Scope**
- Native compilation or transpilation to other languages
- Advanced GUI or IDE integrations
- Advanced features (OOP, multithreading, etc.)

---

## 4. Risks

| Risk                                | Mitigation Strategy                                                  |
|-------------------------------------|----------------------------------------------------------------------|
| Confusion due to multilingual syntax| Define strict grammar rules and provide clear error messages         |
| Complex translation maintenance     | Use a centralized i18n system                                        |
| Low initial adoption                | Actively promote on GitHub, forums, and educational communities      |
| High documentation workload         | Develop documentation alongside feature implementation               |

---

## 5. High-Level Plan & Timeline

### 🗂️ Project Phases

| Phase                     | Weeks       | Key Deliverables                                                     |
|--------------------------|-------------|-----------------------------------------------------------------------|
| ✅ Idea Development       | Weeks 1–2   | ✔ Educational concept validated, ✔ Target audience defined           |
| 🔄 Project Charter        | Weeks 3–4   | 🔹 Charter document finalized, 🔹 SMART goals established             |
| ⏳ Technical Documentation| Weeks 5–6   | 🔹 Alphalang grammar, 🔹 Interpreter architecture documented         |
| ⏳ MVP Development        | Weeks 7–10  | 🔹 Multilingual interpreter (FR/EN), 🔹 Basic tutorials implemented|
| ⏳ Project Closure        | Weeks 11–12 | 🔹 Public GitHub release, 🔹 Final presentation and feedback round   |

---

### 📊 Gantt Chart (Text View)

Phase                         | W1 | W2 | W3 | W4 | W5 | W6 | W7 | W8 | W9 | W10 | W11 | W12 |
------------------------------|----|----|----|----|----|----|----|----|----|-----|-----|-----|
Idea Development              | ██ | ██ |    |    |    |    |    |    |    |     |     |     |
Project Charter               |    |    | ██ | ██ |    |    |    |    |    |     |     |     |
Technical Documentation       |    |    |    |    | ██ | ██ |    |    |    |     |     |     |
MVP Development               |    |    |    |    |    |    | ██ | ██ | ██ |  ██ |     |     |
Project Closure               |    |    |    |    |    |    |    |    |    |     | ██  | ██  |