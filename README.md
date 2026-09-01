# Relational Database & CLI Automation Suite (freeCodeCamp)

A comprehensive showcase of all certification projects completed for the freeCodeCamp **Relational Database Certification**. This portfolio demonstrates hands-on expertise in relational database modeling with PostgreSQL, robust SQL querying, and workflow automation using Linux Bash scripting.

---

## 📌 Overview

This suite covers core database and scripting paradigms:
* **Relational Schema Design & Normalization:** Implementing clean entity-relationship architectures using Primary/Foreign Key constraints, uniqueness checks, cascading actions, and data type validation.
* **Automated Data Ingestion & ETL:** Utilizing Bash scripts and PostgreSQL's native `\copy` / `INSERT` workflows to parse CSV files and populate normalized tables without duplication.
* **Interactive CLI Applications:** Building menu-driven terminal tools with dynamic user input handling, string manipulation, and real-time database queries via `psql`.
* **Database Migrations & Data Cleaning:** Refactoring existing schemas, applying column constraints, casting types, and sanitizing legacy records using SQL DDL/DML scripts.

---

## 📂 Included Certification Projects

| Project | Core Stack | Description | Repository |
| :--- | :--- | :--- | :---: |
| **World Cup Database** | PostgreSQL, Bash | Reads CSV match records via Bash, dynamically resolves unique team IDs, and performs complex multi-table analytical SQL queries. | [View Repo ↗](https://github.com/janf1997-sys/freecodecamp-worldcup) |
| **Salon Appointment Scheduler** | PostgreSQL, Bash | Terminal-based booking engine that handles dynamic customer registration, service selection, and appointment scheduling. | [View Repo ↗](https://github.com/janf1997-sys/freecodecamp_salon) |
| **Periodic Table Database** | PostgreSQL, Bash | CLI search tool with schema refactoring, data normalization, regex argument parsing, and formatted output generation. | [View Repo ↗](https://github.com/janf1997-sys/freecodecamp-periodic-table) |
| **Number Guessing Game** | PostgreSQL, Bash | Command-line game featuring user tracking, persistent game-state statistics, and database-backed best-game metrics. | [View Repo ↗](https://github.com/janf1997-sys/freecodecamp-number-guess) |
| **Celestial Bodies Database** | PostgreSQL, SQL | Multi-tier relational schema modeling galaxies, stars, planets, and moons with strict 1:N and N:M constraints. | [View Repo ↗](https://github.com/janf1997-sys/freecodecamp_celestial-bodies) |

---

## 🛠️ Technical Skill Set

* **Database Engine:** PostgreSQL
  * Relational Schema Architecture (1:1, 1:N, N:M)
  * Constraints (`PRIMARY KEY`, `FOREIGN KEY`, `UNIQUE`, `NOT NULL`, `CHECK`)
  * Data Manipulation & Querying (Complex `JOIN`s, Subqueries, Aggregations, Grouping)
  * Schema Migrations (`ALTER TABLE`, Data Type Conversions, Safe Cascades)
* **Shell Scripting:** Bash (`/bin/bash`)
  * Non-interactive & interactive database communication via `psql`
  * Stream processing, pipeline routing (`xargs`, `sed`, `awk`, `cut`)
  * Control flow, input sanitization, and deterministic CLI menus
* **Development & Environment:** Git, Linux (Ubuntu/Debian), POSIX Standards
