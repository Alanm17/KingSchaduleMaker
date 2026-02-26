# 👑 KingSchadule 

> **A comprehensive, enterprise-grade employee scheduling and staff management system.**

[picture here: A high-quality banner image showing a beautiful multi-device mockup (laptop, tablet, and mobile) displaying the Dashboard, Schedule Maker, and Staff Hub]

Welcome to **KingSchadule**, a powerful suite designed to streamline workforce operations. Built to handle complex 24/7 rotational requirements, time-off requests, and instant schedule distribution, KingSchadule provides everything needed to manage a fast-paced work environment like King Kebab efficiently.

---

## ✨ Key Features & Modules

### 1. 📅 Advanced Employee Scheduling
A powerful, drag-and-drop schedule maker designed for complex, 24/7 operational requirements.
* **Smart Drag-and-Drop:** Intuitive shift assignments and reordering powered by DnD Kit.
* **24/7 Coverage Optimization:** Handles overnight shifts and dynamic availability with ease.
* **Replacement Staff Modal:** Managers can seamlessly swap out staff members and handle shift replacement requests on the fly.
* **Auto-Save & Instant Sharing:** Changes are persisted to the cloud immediately. Managers can generate an image of the weekly schedule and share it directly with staff with one click.
* **Mobile-Optimized Interactions:** Carefully designed touch interactions prevent accidental selections while scrolling on phones.

[picture here: A multi-column view showing the Schedule Maker interface, highlighting the drag-and-drop shift assignments and the "Share Schedule" functionality]

### 2. 👑 Admin Dashboard & Operations
The central nervous system for schedule managers and owners.
* **Historical Metrics & Overviews:** Track overall staff performance and logged hours.
* **Staff Hub:** Add and manage employee profiles, track staff availability, and monitor shift preferences from a single location.
* **Request Management Workspace:** A dedicated, searchable inbox for approving or denying shift swaps and time-off requests based on real-time schedule availability.

[picture here: The Admin Dashboard overview highlighting daily shift coverage, active staff charts, and pending time-off requests]

---

## 🛠️ Technical Stack & Architecture

Although the source code is private, the architecture leverages modern web technologies built for scale, speed, and developer experience.

### Core Framework & Build Tools
* **React 19:** The core UI library used to build the responsive application.
* **TypeScript:** Ensures static typing to catch errors early and improve developer experience.
* **Vite:** The lightning-fast build tool and development server running the project.

### State Management & Backend
* **Zustand (`zustand`):** A small, fast, and scalable state management solution handling the complex state of the schedules and staff.
* **Firebase & Firebase Admin (`firebase`, `firebase-admin`):** Used for real-time database synchronization (Firestore) and secure user authentication.

### UI & Styling
* **Tailwind CSS (`tailwindcss`):** A utility-first CSS framework for rapid and highly customized styling.
* **Lucide React (`lucide-react`):** A beautiful, consistent icon library used throughout the dashboard and schedule views.
* **React Router (`react-router-dom`):** Handles client-side routing between the different modules (Dashboard, Schedule, Staff, etc.).
* **React Hot Toast (`react-hot-toast`):** Provides clean, non-intrusive notification popups for system events (e.g., "Schedule Saved").

### Specialized Functionality
* **DnD Kit (`@dnd-kit/core`, `@dnd-kit/sortable`):** A modern, lightweight, and performant drag-and-drop toolkit powering the shift reordering in the Schedule Maker.
* **html2canvas (`html2canvas`):** Automatically generates shareable image exports of the weekly schedules directly from the DOM framework.
* **Recharts:** Renders rich, interactive data visualizations on the administrative dashboards regarding shift coverages.
* **ESLint (`eslint`, `typescript-eslint`):** Enforces code quality and robust formatting rules.

### Notable Engineering Achievements

* **Zero-Lag State Synchronization:** By pairing Zustand stores directly with Firebase real-time listeners, the dynamic schedule state propagates globally with millisecond latency.
* **Sophisticated File Export:** Implemented `html2canvas` and built custom logic to allow managers to instantly export complex, scrolling DOM schedule views into shareable high-res images directly to their devices.
* **Performant Virtualization:** Solved UI stuttering during heavy drag-and-drop actions by utilizing effective virtualization and targeted re-rendering strategies across the massive scheduling grid.

---

## 🔒 Project Status

This project is a **private, proprietary system** developed for specific operational needs and is not open for public contribution.

[picture here: A clean, minimalist graphic of the KingSchadule logo or project insignia to conclude the document]

---
*Designed & Engineered for Operational Excellence.*
