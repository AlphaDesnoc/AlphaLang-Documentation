# 📄 Development Report – Programming Language Project

## 1. 💡 Ideas Considered

### Idea 1: Create a data science-oriented language (simplified Python style)

**Strengths**:
- High demand in the industry.  
- Possibility to build simplified native libraries.

**Weaknesses**:
- High complexity in handling matrix and numerical computations efficiently.  
- Hard to stand out against Python or Julia.

**Reason for rejection**:
- Too ambitious for the available time frame.  
- Would require a complex math backend, not feasible for a final-year project.

---

### Idea 2: A front-end-oriented language with CSS/JS-inspired syntax

**Strengths**:
- Familiar syntax for many developers.  
- Easy integration with web environments.

**Weaknesses**:
- Too close to JavaScript, risking lack of originality.  
- Little added value if it ends up being just a “sub-JS.”

**Reason for rejection**:
- Too redundant and not innovative enough.

---

### Final Idea Selected: A simple, dynamically typed language based on JavaScript with a clean, educational, and multilingual syntax

**Strengths**:
- Great for learning the basics of programming.  
- Full control over how it works (custom interpreter).  
- Minimalist syntax = fewer syntax errors for beginners.

**Weaknesses**:
- Limited features compared to “serious” languages.  
- Requires building an interpreter from scratch.

**Reason for selection**:
- Technically feasible and pedagogically valuable.  
- A strong showcase of my skills in parsing, execution, and language design.

---

## 2. 🎯 MVP Summary

**Language Name**: ***AlphaLang***
**Objective**: Create a simple and accessible language to help users understand programming fundamentals without the overhead of complex syntax.

### Key Features:
- JavaScript-inspired but simplified syntax.  
- Dynamic variable system.  
- Control structures: `if`, `while`, `for`, `function`.  
- Clear and simple error handling.  
- Interpreter written in TypeScript for easy web integration.  
- Support for both French and English syntax.

### MVP Justification:
- Demonstrates all essential steps in creating a programming language: grammar, parsing, interpretation, error handling, memory.  
- Small enough in scope to complete within the project timeline.  
- Easy to showcase and test live during the final presentation.

### Potential Impact:
- Can serve as a teaching tool.  
- Integrates well into educational platforms.  
- Could be extended later to support JavaScript transpilation.

---

## 3. 👥 Team Formation & Development Process

**Team Setup**:  
Individual project – everything was designed, developed, and tested by myself.

**Development Process**:

- **Needs Analysis**:  
  Identify what I wanted to learn and demonstrate (parsing, execution, language design).

- **Research**:  
  Studied the architecture of existing languages (Lox, Python, JS).

- **Prototype**:  
  Created a minimal grammar.  
  Wrote a basic interpreter in TypeScript.

- **Testing & Validation**:  
  Added test files.  
  Debugged using detailed logging.

- **Iterations**:  
  Gradually added support for functions, loops, and custom errors.  
  Partially refactored the memory system.

- **Documentation & Finalization**:  
  Wrote user documentation.  
  Prepared a technical presentation of the language’s internal mechanisms.
