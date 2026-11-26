# 📘 Course 11: Object-Oriented Programming (Applications)
> **"From OOP Theory to Production-Grade Architecture: Building Scalable, Layered Systems in C++"**

This course represents the practical culmination of the Object-Oriented Programming track. Moving beyond isolated class exercises, Course 11 focuses on **System Architecture, Separation of Concerns, and Real-World Application Engineering**. By building reusable utility libraries (`clsUtil`, `clsInputValidate`) and architecting a complete, multi-module **Bank & Currency Exchange System** across 10 progressive extensions, this stage bridges OOP concepts with enterprise software design.

---

## 🔗 Key Resources & Capstone Deliverables

### 🏗️ Production-Grade Capstone System & Libraries
* 🏦 **[Capstone Project: OOP Bank & Currency Exchange System](https://github.com/Hazem-Hamada/OOP-Bank-And-Currency-Exchange-System):** A full-scale, 3-tier console application featuring Client/User CRUD, Bitwise permissions, encrypted file storage, audit logging, and a complete Currency Exchange module.
* 🧰 **[Utility & Validation Libraries (`clsUtil` & `clsInputValidate`)](https://github.com/Hazem-Hamada/OOP-Bank-And-Currency-Exchange-System):** Reusable header-only C++ libraries providing defensive input validation, randomization, and encryption helpers.
* 🚀 **[Main Projects Repository](https://github.com/Hazem-Hamada/Projects-From-The-Roadmap-Of-Algorithms-And-Problem-Solving-Courses):** Gallery of all integrated systems and libraries built across the roadmap.

### 🌐 Social & Technical Write-Ups
* 🎓 **[LinkedIn: Course 11 Completion & System Architecture Showcase](ضع_رابط_منشور_كورس_11_هنا_بعد_الرفع):** *[رابط مؤقت: ضع رابط منشور كورس 11 هنا بعد الرفع]* Architectural breakdown of decoupling UI from Business Logic, security extensions, and building scalable OOP systems.

---

## 🧠 The "Layered Architecture" Mindset
In this stage, the focus shifted from designing individual classes to **orchestrating a 30+ file software system** where every layer has a single, isolated responsibility.

**Key Architectural Pillars:**
* **Decoupled UI & Business Logic:** Enforced strict isolation between domain classes (`clsBankClient`, `clsUser`, `clsCurrency`) and console screens (`clsScreen` hierarchy) with zero `cout`/`cin` inside core logic.
* **Screen Inheritance Hierarchy:** Centralized shared UI behaviors—header rendering, active session display, system timestamps, and permission checks—inside a base `clsScreen` class inherited by 20+ screens.
* **Enterprise Security & Auditing:** Implemented a 3-attempt login lockout, Bitwise role-based permissions, password encryption at rest, and persistent audit logs (`LoginRegister` & `TransfersLog`).
* **Generic & Defensive C++:** Built `clsInputValidate` to guard against stream failures and applied **Template Functions/Classes** for type-agnostic components.

---

## 🛠️ Technical Skills Demonstrated
* **System Architecture:** 3-Tier Layered Design (Presentation, Business Logic, Data Persistence).
* **OOP Execution:** Multi-level Inheritance, Polymorphism, Pure Virtual Interfaces, and Class Composition.
* **Security & Auditing:** Bitwise RBAC, Password Encryption, Brute-Force Lockout, and Activity Logging.
* **Code Organization:** Structuring a 30+ file codebase into clean, single-responsibility header libraries (`.h`).

---

## 🎓 Final Outcome
Completing Course 11 proves the ability to architect, extend, and maintain complex, multi-file Object-Oriented systems without breaking existing functionality—establishing a solid engineering foundation for **Data Structures**, **Algorithms**, and **Backend Development**.

---
**Developed By Eng. Hazem Hamada**
