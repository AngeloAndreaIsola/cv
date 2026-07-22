# Master Software Engineering Experience

This record summarizes my technical work across various projects, based on repository analysis and git history.

---

## CAT (Category Analysis & Tooling) Suite
A comprehensive suite of tools for transaction classification, data parsing, and infrastructure management in an enterprise procurement AI context.

### Technologies
- Python (Django, FastAPI, SQLAlchemy)
- ML: BERT (transformers), Sentence-Transformers, FAISS
- Databases: PostgreSQL, MySQL
- Cloud/Infrastructure: Google Cloud Platform (Vertex AI, Cloud Run, BigQuery, Pub/Sub, Cloud Build), Terraform, Docker
- Testing: Cypress, Pytest, Jest

### Responsibilities & Key Accomplishments
- **Pipeline Engineering:** Engineered machine learning pipelines using Vertex AI for transaction classification (zero-shot) and grouping (BERT-based).
- **Data Engineering:** Developed robust parsing systems for heterogeneous client data (Excel, CSV) into standardized schemas for procurement analysis.
- **CI/CD:** Automated deployment processes using Cloud Build and Terraform; implemented integration testing suites using Cypress and Docker for reproducible environments.
- **Analytics Dashboard:** Built Streamlit dashboards to visualize data, monitor ML performance, and manage taxonomy approvals for enterprise clients.

### Technical Challenges
- **Transaction Grouping:** Solved high-dimensional matching challenges using FAISS vector similarity search, optimized by preprocessing pipelines.
- **GCP Integration:** Managed secure, automated deployments of data pipelines into multi-tenant GCP environments.

---

## GroceryApp / Recipe Platform
A full-stack platform for smart grocery management and meal planning.

### Technologies
- **Backend:** FastAPI, SQLAlchemy, PostgreSQL, Redis
- **Frontend:** React, TypeScript, Vite, Zustand, Tailwind CSS
- **Infrastructure:** Docker, Cloud Run

### Key Accomplishments
- Implemented core recipe discovery and automated meal planning logic.
- Integrated automated classification for user-uploaded grocery items (e.g., Instagram saved posts).
- Developed a scalable architecture supporting third-party API integrations.

---

## Wishlist App
A personal wishlist management application with self-hosted backend.

### Technologies
- **Backend:** Python, FastAPI, PostgreSQL/SQLite
- **Scraping:** Playwright, httpx
- **Frontend:** React, Vite

### Key Accomplishments
- Implemented item scraping logic using Playwright to extract product metadata.
- Engineered a seamless full-stack integration where the frontend is built into the backend static files for easy deployment.

---

## WhichLLM
A CLI utility to identify the most suitable local LLM based on user hardware.

### Technologies
- Python, Hugging Face, GGUF artifacts, GPU/RAM detection utilities.

### Key Accomplishments
- Developed automated detection logic for GPU/RAM resources.
- Optimized model ranking algorithms to provide hardware-aware LLM recommendations.
