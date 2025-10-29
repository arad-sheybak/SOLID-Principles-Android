# 🚀 SOLID Principles in Android

A **real-world Android project** demonstrating **SOLID principles** using **Kotlin** and **Jetpack Compose**.  
Each principle is implemented as a **separate, modular feature** to showcase clean architecture and production-ready patterns.

---

## 📘 What is SOLID?
SOLID is an acronym for five principles of object-oriented programming:
- **S** - Single Responsibility Principle (SRP)
- **O** - Open/Closed Principle (OCP)
- **L** - Liskov Substitution Principle (LSP)
- **I** - Interface Segregation Principle (ISP)
- **D** - Dependency Inversion Principle (DIP)

These principles improve code readability, maintainability, and scalability in large applications.

---

## 🧩 Features / Modules
| Principle | Module Path | Description |
|-----------|------------|-------------|
| SRP | [feature-srp-user](./feature-srp-user) | User management with separated responsibilities |
| OCP | [feature-ocp-payment](./feature-ocp-payment) | Extensible payment processors without modifying existing code |
| LSP | [feature-lsp-auth](./feature-lsp-auth) | Subtypes of users substitutable without breaking the system |
| ISP | [feature-isp-feed](./feature-isp-feed) | Segregated interfaces for feed interactions |
| DIP | [feature-dip-notification](./feature-dip-notification) | High-level modules depend on abstractions for notifications |

---

## 🛠 Tech Stack
- **Kotlin**
- **Jetpack Compose**
- **Hilt (Dependency Injection)**
- **MVVM + Clean Architecture**
- **Coroutines + Flow**

---

## 🏷️ Tags / Topics
`android` `kotlin` `jetpackcompose` `solidprinciples` `cleanarchitecture` `mvvm` `opensource`

---

## 📂 Project Structure
    SOLID-Principles-Android/
    ├── app/
    ├── feature-srp-user/
    ├── feature-ocp-payment/
    ├── feature-lsp-auth/
    ├── feature-isp-feed/
    ├── feature-dip-notification/
    ├── build.gradle.kts
    └── settings.gradle.kts


---

## 🔗 Next Steps
- Explore each module's README for detailed explanation
- Run `app` module to see all features in action
