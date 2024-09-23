# 🚀 Astro Bookings

> Sample project for teaching full-stack development with modern technology (`Angular, NestJS, Postgres, MongoDB`) and proven best practices (DDD, unit test with `Jest`, E2E test with `Cypress`).

### Company mission

**🚀 AstroBookings** is a fictitious space tourism company that wants a platform for rocket _agencies_ to offer _bookings_ for their launches to _travelers_ who want to fly into space.

## 📡 The Project

Create a solution for financial and IT employees, and also give access to agencies and travelers in order to manage their launches, bookings and financial operations.

- [**0. 📋 Read the Project Briefing**](./0-project.briefing.md)
- [_Go to the implementation_](#-the-implementation)

Or keep reading the project analysis and solution design.

### 🧑‍🔬 Analysis

- [0. Stakeholders Letters](./0-requirements/0-stakeholders.letters.md)
- [1. Domain Requirements](./1-analysis/1-domain.requirements.md)
- [2. System Requirements](./1-analysis/2-system.requirements.md)

## 🛰️ The Solution

The solution is a set of web applications made with `Angular` that consume several REST APIs made with `NestJS`. Data is stored in `Postgres` and `MongoDB` databases.

### 📝 Design

- [1. System Architecture](./2-design/2-system.architecture.md)
- [2. Data Model](./2-design/3-model.erd.md)
- [3. Solution Domain specifics](./2-design/4-solution.domain.md)

## 🧑‍💻 The Implementation

Those are the repositories of the implementation:

### 🧑‍💼 API Service repositories

> ⚠️ ToDo: link to Airbus Repos

- [0. **System API**](https://github.com/AirBus-Bootcamp/0_ab_system_api)
- [4. **Notify API**](https://github.com/AirBus-Bootcamp/4_ab_notify_api)

### 📇 DataBase schemas

- [1. **SystemDB** schema](./3-implementation/5_0-system.schema.md)
- [2. **OperationsDB** schema](./3-implementation/5_1-operations.schema.md)
- [3. **CacheDB** schema](./3-implementation/5_2-cache.schema.md)

---
