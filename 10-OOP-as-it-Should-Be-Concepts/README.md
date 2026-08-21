# 📘 Course 10: Object-Oriented Programming (Concepts)
> **"Bridging Imperative Logic and Software Architecture: Mastering Object-Oriented Design & Memory Mechanics"**

This course is the cornerstone of the entire Software Engineering track. Marking the transition from procedural scripting ("how to write code") to **System Design and Architecture ("how to structure maintainable software")**, Course 10 establishes the deep OOP mindset needed for large-scale application development. Beyond syntax, it focuses on object memory layouts, lifecycle management, encapsulation, dynamic polymorphism, and constructing enterprise-ready utility libraries.

---

## 🔗 Key Resources & Capstone Deliverables

### 🏗️ Production-Grade Utility Libraries & Projects
* 🔤 **[clsString Utility Library](https://github.com/Hazem-Hamada/Projects-From-The-Roadmap-Of-Algorithms-And-Problem-Solving-Courses/tree/main/Course%2010%3A%20Projects/Project%201%20-%20String%20Library):** A dual-paradigm C++ library encapsulating procedural text algorithms into static utilities and instance-bound methods.
* 📅 **[clsDate & clsPeriod Libraries](https://github.com/Hazem-Hamada/Projects-From-The-Roadmap-Of-Algorithms-And-Problem-Solving-Courses/tree/main/Course%2010%3A%20Projects/Project%202%20-%20Date%20Library):** An enterprise date-engineering suite handling complex calendar arithmetic, leap-year calculations, working-day validation, and intersecting **Period Overlap/Length algorithms**.
* 🚀 **[Main Projects Repository](https://github.com/Hazem-Hamada/Projects-From-The-Roadmap-Of-Algorithms-And-Problem-Solving-Courses):** The unified repository showcasing all integrated applications built across the roadmap.

### 🧩 Exercises & Core Homeworks
* 📂 **[View Hands-On OOP Exercises](./01-Class-Exercises/):** Object-oriented implementations covering class hierarchies (`Person`, `Employee`, `Developer`), static member management, and object composition.

### 🌐 Social & Technical Write-Ups
* 📢 **[LinkedIn: String Library Architecture Deep-Dive](ضع_رابط_منشور_clsString_هنا_بعد_الرفع):** *[ضع رابط منشور clsString هنا بعد الرفع]* Technical breakdown of Dual API Design (Static vs Instance) in C++.
* 🎓 **[LinkedIn: Course 10 Completion & Date/Period Showcase](ضع_رابط_منشور_الكورس_هنا_بعد_الرفع):** *[ضع رابط منشور الكورس هنا بعد الرفع]* Architecture breakdown of `clsDate` and the shift toward Object-Oriented design patterns.

---

## 🧠 Architectural & Technical Mastery

### 1. Memory Mechanics & Object Lifecycles
* **Memory Management:** Understanding object allocation across Stack and Heap, member offset layouts, and the implicit `this` pointer in instance contexts.
* **Lifecycle Control:** Implementing Default Constructors, Parameterized Constructors, Deep Copy Constructors (`Copy-Constructor`), and automated RAII deallocation via Destructors.
* **Optimization & Data Structures:** Minimizing memory overhead by passing objects via `const` references (`ByRef`) vs values (`ByVal`), alongside managing dynamic arrays and `std::vector` of objects.

### 2. Encapsulation & Interface Design
* **Data Hiding & Properties:** Guarding internal state using access specifiers (`private`, `protected`, `public`) and exposing controlled mutation via `Set`/`Get` property methods.
* **Class vs Struct:** Clarifying semantic and functional differences in C++ (default visibility modes) to make informed design choices.
* **Physical Organization:** Modularizing architecture by building standalone, header-only C++ libraries (`.h`) to enforce separation of concerns.

### 3. Inheritance, Polymorphism & Binding
* **Hierarchy Design:** Constructing single, multilevel, and multiple inheritance trees while managing visibility modes and base-class constructor delegation.
* **Polymorphism & vtables:** Leveraging virtual functions, pure virtual functions, and abstract classes to build contract-driven interfaces, understanding early (static) vs late (dynamic) binding.
* **Friend Operations:** Controlled encapsulation bypass using Friend Classes and Friend Functions for tightly coupled domain entities.

---

## 🛠️ Technical Skills Demonstrated
* **Dual API Design:** Exposing both stateless `static` methods and state-bound `instance` methods within unified class structures.
* **Abstract Interface Engineering:** Defining clean system contracts using pure virtual interfaces.
* **Domain Modeling:** Converting real-world entities into encapsulated, reusable C++ classes.
* **Clean Code & Physical Design:** Writing self-documenting code organized into isolated, reusable libraries.

---

## 🎓 Final Outcome
Completing this course marks a fundamental milestone: transitioning from writing functional scripts to architecting robust, modular software systems. This foundation prepares the way for advanced Data Structures, Design Patterns, and Enterprise Architecture.

---
**Developed By Eng. Hazem Hamada**
