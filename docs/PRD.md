# Product Requirements Document (PRD)

## 1. Product Overview

The **Caravan Technician Support Portal** is a centralized platform designed to help caravan repair technicians across Australia easily access caravan model data, parts, and repair instructions. The portal serves as a structured interface for manufacturers to upload caravan specifications, while offering technicians an intelligent search and support experience — including an AI assistant that aids in diagnosing and resolving repair issues.

This prototype aims to demonstrate how AI tools can be used by a product manager to design and validate a product concept — from design to documentation — without traditional engineering support, before moving into MVP execution.

---

## 2. Problem Statement

Caravan service technicians lack centralized, manufacturer-approved access to up-to-date model-specific part details and repair instructions. Repair jobs are often delayed or done improperly due to missing documentation or part mismatches. Manufacturers, in turn, lack a scalable way to distribute technical documentation to field technicians.

---

## 3. Goals

- **Streamline access to caravan model and part information** for technicians via VIN lookup
- **Enable manufacturers** to upload legacy data and sync future models via API
- **Support technician repair workflows** with repair steps and diagrams
- **Introduce AI-assisted troubleshooting** for improved efficiency and learning

---

## 4. Target Users

### Technician
- Search caravans by VIN
- View part diagrams and repair instructions
- Interact with AI assistant for troubleshooting
- Read-only access

### Manufacturer
- Upload caravan data (CSV or API)
- Edit parts/repair documents
- View analytics (in future)
- Edit permissions

### Admin
- Override access
- Manage users, manufacturers, and data integrity

---

## 5. Key Features (MVP Scope)

| Feature                              | Description                                                                 |
|--------------------------------------|-----------------------------------------------------------------------------|
| VIN Search                           | Technicians can enter VIN to retrieve caravan details                       |
| Part Explorer                        | Exploded view of parts with repair/replacement instructions                 |
| Manufacturer Upload Interface        | Upload legacy data (CSV) and API endpoint for new data                      |
| AI Assistant (Phase 1 - Retrieval)   | AI chatbot retrieves repair instructions and documentation                  |
| Role-based Access Control            | Technician (view), Manufacturer (edit), Admin (full)                        |
| Sample Data (New AGE caravans)       | Example dataset used to demo search and repair logic                        |

---

## 6. Non-MVP / Future Features

- AI-guided interactive repair flow (decision tree)
- Mobile-first technician interface
- Real-time diagnostics integration via sensors (if available)
- Manufacturer performance dashboards

---

## 7. Technical Considerations

- VIN is primary unique identifier for caravans
- API endpoint for future manufacturer uploads (REST-based)
- AI assistant built using RAG (Retrieval-Augmented Generation)
- Frontend may be generated from Figma → Framer for prototype

---

## 8. Success Metrics (for prototype phase)

- Recruiter/stakeholder can explore the prototype with zero technical friction
- Clear narrative around problem, users, and solution
- Demonstrated use of AI for design, documentation, and guidance
- Feedback from 2+ domain experts validates real-world value

---

## 9. Tools Used

- **Figma** – UI Design (via AI prompt + layout tweaks)
- **Framer** – Interactive prototype
- **ChatGPT** – PRD creation, AI prompt generation
- **GitHub** – Public repository to host all assets
- **New AGE (mock data)** – Used for example caravan entries


