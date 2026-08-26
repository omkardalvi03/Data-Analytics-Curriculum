# Module 3: Advanced Relational Database Engineering & Query Optimization

This folder contains comprehensive database scripts detailing production-level relational database architecture, optimization strategies, and programmatic data workflows.

## 🗄️ Advanced Skills & Concepts Mastered

### 1. Database Performance & Optimization (DDL)
* **Performance Tuning Indexing:** Architected single and multi-column composite database keys (`CREATE INDEX idx_table1_major_gpa`) to dramatically reduce query search latencies on production tables.
* **Virtual Layering (Views):** Structured reusable, abstract presentation layers (`CREATE VIEW high_gpa_students`) to securely isolate underlying tables from frontend requests.

### 2. Relational Analytics & Multi-Table Operations (Joins)
* **Comprehensive Set Theory:** Executed advanced structural table relationships using `INNER JOIN`, contextual mutations via `LEFT JOIN` / `RIGHT JOIN`, and horizontal grid mergers using emulation matrices (`FULL JOIN` via `UNION`).
* **Combinatorics Engines:** Built structural cross-multiplications (`CROSS JOIN`) to model complex matching combinations across unrelated tables.

### 3. Programmatic Workflows & Database Control
* **Stored Procedures:** Engineered parameterized, repeatable database functions (`CREATE PROCEDURE`) utilizing input argument parameters (`IN STUDENT_ID INT`) and variable token checks (`DELIMITER //`).
* **Conditional Record Mergers:** Implemented strict transactional safety guards (`INSERT INTO ... WHERE NOT EXISTS`) to ensure structural data integrity during batch runs.

### 4. Advanced Subqueries & Deep Data Mutation (DML)
* **Nested Analytics Filters:** Structured multi-tiered, sub-selected aggregations (`HAVING AVG(GPA) = (SELECT MAX...)`) to extract maximum data boundaries.
* **Multi-Table Batch Modifications:** Developed cross-referenced mutation pipelines using nested lookup logic to perform safe updates and cascading drops (`UPDATE` / `DELETE ... WHERE ID IN (SELECT...)`).