# Jesús Blanco — Full-Stack Software Developer

Desarrollador de Software Full-Stack con núcleo en **TypeScript (React 19)** y **Python (FastAPI)**, enfocado en **modelado de datos transaccionales, consistencia relacional e infraestructura automatizada**. Experiencia diseñando y desplegando sistemas de grado de producción desde entornos restringidos (hosting compartido cPanel/WSGI) hasta arquitecturas contenerizadas en VPS Linux (Docker Compose, Nginx).

---

### 🚀 Sistemas Transaccionales en Producción

#### 1. [Yanesu Shisutemu](https://github.com/Jesus-1205/yanesu-shisutemu) — POS & ERP Bimoneda de Alta Disponibilidad
*Plataforma transaccional para retail comercial desplegada en producción continua.*
* **Arquitectura:** Desacoplada con backend en FastAPI (SQLAlchemy 2.0 / PostgreSQL 16) y frontend en React 19 (TypeScript, Zustand, Tailwind CSS v4).
* **Métricas:** Reducción del **65.8% en latencia** (184 ms a 63 ms) y **-76.3% en transferencia de payload** mediante push-down de agregaciones SQL nativas.
* **Calidad:** Suite con **2.662 pruebas automatizadas** (972 en Pytest y 1.690 en Vitest) bajo metodología TDD/SDD.
* **Dual-Deploy:** Contenerizado en VPS Linux (Docker Compose) y cliente de escritorio nativo de bajo consumo (~30 MB RAM) con **Tauri 2 (Rust)**.

#### 2. [Taller-Admin v2.0](https://github.com/Jesus-1205/Taller-Admin-v2) — ERP Automotriz & Migración ETL
*Modernización de sistemas legados y arquitectura transaccional para centro de servicios automotrices.*
* **Migración ETL:** Procesamiento e ingesta de **+7.000 registros y presupuestos históricos** (8 años en hojas de cálculo) hacia un datastore híbrido (3NF relacional + JSON inmutable).
* **Consistencia:** Algoritmo transaccional con bloqueo pesimista (`.with_for_update()`) para particionamiento atómico de órdenes en formas continuas físicas.
* **Producción:** +6 meses de operación continua ininterrumpida sobre hosting compartido (cPanel / Phusion Passenger / Cron).

---

### 🛠️ Core Tech Stack

* **Lenguajes:** TypeScript, JavaScript (ES6+), Python 3.12+, SQL, Bash CLI.
* **Frontend:** React 19, Zustand, Tailwind CSS v4, Vite, HTML5 Semántico, Jinja2.
* **Backend:** FastAPI, SQLAlchemy 2.0, Pydantic v2, Alembic (Batch Mode), Node.js.
* **Bases de Datos:** PostgreSQL 16, SQLite 3 (journal_mode=DELETE), Modelado Relacional (3NF & Historical Snapshots).
* **DevOps & Infra:** Docker, Docker Compose, Linux Server Administration, Nginx Reverse Proxy, n8n (M2M Workflows & Telegram Bots).
* **Calidad de Software:** Spec-Driven Development (SDD), Test-Driven Development (TDD), Pytest, Vitest, HTTPX.

---

### 📜 Certificaciones Verificadas

* **[Relational Database Developer Certification (~300h)](https://freecodecamp.org/certification/jesus-1205/relational-databases-v9)** — *freeCodeCamp* (Sep 2026)  
  *Especialización práctica en PostgreSQL, normalización relacional, scripting en Bash y pipelines de datos.*

* **[SQL Associate Certification](https://www.datacamp.com/certificate/SQA0013749388160)** — *DataCamp* (Jun 2026 | ID: `SQA0013749388160`)  
  *Evaluación profesional en diseño relacional, manipulación avanzada de datos y optimización de consultas.*

* **[JavaScript Developer Certification (~300h)](https://freecodecamp.org/espanol/certification/jesus-1205/javascript-v9)** — *freeCodeCamp* (Ago 2026)  
  *Algoritmos avanzados, estructuras de datos complejas y programación funcional con ES6+.*

* **[GitHub Foundations (9h)](https://www.datacamp.com/completed/statement-of-accomplishment/track/c6004cb53a4bcfb5ad507698f90bddbce187c35c)** — *DataCamp* (Jun 2026 | Credencial `#862,499`)  
  *Control de versiones avanzado, flujos colaborativos y fundamentos de GitHub Actions.*

---

### 📬 Contacto & Enlaces

* **Correo:** [jesusenriqueblanco16@gmail.com](mailto:jesusenriqueblanco16@gmail.com)
