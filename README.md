# Database Management Systems (DBMS) Lab File

This repository contains the complete lab experiments for Database Management Systems (DBMS), including table schemas, insert scripts, advanced SQL queries, stored procedures, triggers, views, CTEs, normalization, transaction control, indexing, query optimization, and verified execution outputs.

---

## 📚 List of Experiments

| Exp No. | Title / Topic | Markdown File | Description / Aim |
| :---: | :--- | :--- | :--- |
| **03** | **Relational Database Design & Basic Queries** | [DBMS_Experiment_03.md](./DBMS_Experiment_03.md) | Create Employee–Department–Project database, populate with 30 employees, 5 departments, and 8 projects. Demonstrate Selection, Projection, Aggregate Functions, GROUP BY, HAVING, CASE, and ORDER BY. |
| **04** | **Complex Joins, Subqueries & Query Execution Plans** | [DBMS_Experiment_04.md](./DBMS_Experiment_04.md) | Demonstrate INNER JOIN, LEFT JOIN, self-join, 3-way join, correlated subqueries, EXISTS, simulated INTERSECT and EXCEPT. Compare execution plans using EXPLAIN. |
| **05** | **Views & Recursive CTEs** | [DBMS_Experiment_05.md](./DBMS_Experiment_05.md) | Create department salary summary and employee hierarchy views, evaluate view updatability rules, and implement recursive Common Table Expressions (CTE) for employee reporting chains. |
| **06** | **Stored Procedures, Triggers & Transactions** | [DBMS_Experiment_06.md](./DBMS_Experiment_06.md) | Implement `transfer_employee` stored procedure with input validation, transaction rollback/commit, salary validation trigger, and audit logging triggers. |
| **07** | **Functional Dependencies & Normalization (UNF to BCNF)** | [DBMS_Experiment_07.md](./DBMS_Experiment_07.md) | Identify functional dependencies in a denormalized Sales table, normalize step-by-step from UNF to 3NF and BCNF, and verify lossless join and dependency preservation. |
| **08** | **Transactions, ACID Properties & Concurrency Control** | [DBMS_Experiment_08.md](./DBMS_Experiment_08.md) | Implement banking-style transactions using BEGIN, COMMIT, ROLLBACK, and SAVEPOINT. Simulate partial failures, transaction isolation levels, and multi-session concurrency. |
| **09** | **Indexing & Query Performance Benchmarking** | [DBMS_Experiment_09.md](./DBMS_Experiment_09.md) | Populate 5,000+ railway booking records, create single-column and composite indexes, and compare execution plans using EXPLAIN and profiling. |
| **10** | **Query Optimization & EXPLAIN Plan Tuning** | [DBMS_Experiment_10.md](./DBMS_Experiment_10.md) | Generate a 10,000+ record dataset, identify and analyze five slow queries with EXPLAIN, optimize via indexing and query rewriting, and benchmark performance improvements. |

---

## 📁 Repository Structure

```
├── DBMS_Experiment_03.md          # Experiment 3 Lab Document
├── DBMS_Experiment_04.md          # Experiment 4 Lab Document
├── DBMS_Experiment_05.md          # Experiment 5 Lab Document
├── DBMS_Experiment_06.md          # Experiment 6 Lab Document
├── DBMS_Experiment_07.md          # Experiment 7 Lab Document
├── DBMS_Experiment_08.md          # Experiment 8 Lab Document
├── DBMS_Experiment_09.md          # Experiment 9 Lab Document
├── DBMS_Experiment_10.md          # Experiment 10 Lab Document
├── pdf/                           # Lab PDF Reports
├── images/                        # Query output execution screenshots
```
