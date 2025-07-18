# Product Requirements Document (PRD)

## Configuration Management System for KaneAI & Test Manager

### 📌 Introduction
The **Configuration Management System** for KaneAI & Test Manager is designed to streamline the process of managing, allocating, and maintaining test configurations and application versions. It enables QA engineers and development managers to efficiently assign configurations to test cases and test runs, and to keep application versions up to date — ensuring robust and flexible test automation at scale.

---

### 🎯 Goals and Objectives
- Simplify the allocation of configurations to test cases and test runs.
- Enable easy creation, editing, and management of configuration types and parameters.
- Maintain and update application versions efficiently within the system.
- Support advanced filtering, including regular expressions, for precise configuration selection.
- Ensure seamless integration with KaneAI and Test Manager for automated test execution.

---

### 🧩 Feature Breakdown

#### ✅ Configuration Types
- **Desktop**: OS, OS Version, Browser, Browser Version, Resolution *(Default)*
- **Real Device**: OS, Manufacturer, Device Name, OS Version, Application *(Optional)*, Cloud Type *(Public/Private)*
- **Virtual Device**: OS, Browser, Manufacturer, Device Name, OS Version

#### ✅ Parameters
- Each configuration type supports relevant parameters as outlined above.

#### ✅ Regular Expression Filtering
- Filter configurations using regex for Manufacturer, Device Name, and OS Version (especially for real devices).

#### ✅ Configuration Allocation
- Allocate configurations to test cases and test runs.
- Includes **bulk actions** and **drag-and-drop** assignment.

#### ✅ Application Maintenance
- Manage, update, and edit application versions (mobile and web).
- Supports versioning, archiving, and promotion.

#### ✅ Filtering System
- Tag-based and advanced filtering for quick configuration selection during test execution.

---

### 👤 User Stories
- As a QA Engineer, I want to quickly allocate the right configurations to my test cases so that I can ensure coverage across devices and platforms.
- As a QA Engineer, I want to use regular expressions to filter real devices by manufacturer or OS version to target specific device groups.
- As a Development Manager, I want to maintain and update application versions in the system, so my team always tests against the latest builds.
- As a QA Engineer, I want to bulk-assign configurations to multiple test cases or runs, saving time on repetitive tasks.
- As a QA Engineer, I want to distinguish between public and private cloud real devices to comply with security and access requirements.

---

### 🚧 Challenges
- Efficiently handling a large and growing number of configurations with fast search and filtering.
- Ensuring smooth integration with Test Manager for automated test execution and reporting.
- Maintaining data consistency when configurations or application versions are updated or deprecated.
- Providing a user-friendly interface for complex filtering (including regex) without overwhelming users.
- Supporting bulk operations and drag-and-drop allocation in a performant way.

---

### 🔝 Prioritization
1. **Configuration Allocation System** – Core to the product, enabling assignment of configurations to test cases and runs.
2. **Filtering System (including regex)** – Essential for managing large configuration sets and targeting specific devices.
3. **Application Maintenance** – Important for keeping test environments up to date and relevant.
4. **Bulk Actions & Drag-and-Drop** – Improves usability and efficiency for power users.

---

### 🔗 Live Preview
You can access the working prototype of the PRD here:  
👉 [Lambda PRD GitHub Pages](https://shrivastavabhishek2004.github.io/Lambda_PRD/)

---

