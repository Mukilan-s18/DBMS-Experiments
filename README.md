# DBMS Experiments 🗄️🔍

[![Oracle](https://img.shields.io/badge/Oracle-Database-red.svg)](https://www.oracle.com/database/)
[![SQL](https://img.shields.io/badge/SQL-Scripts-blue.svg)](https://en.wikipedia.org/wiki/SQL)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📌 Project Overview
This repository contains a comprehensive collection of Database Management System (DBMS) lab experiments. It covers fundamental and advanced SQL concepts, including Data Definition Language (DDL), Data Manipulation Language (DML), advanced queries, subqueries, joins, PL/SQL procedures, and triggers.

The experiments are designed to build a strong foundation in database design, querying, and management using Oracle SQL.

## 🏗️ Experiments and Contents

The repository consists of 16 experimental scripts, each focusing on specific database management concepts:

| Experiment | Focus Area / Description |
| :---: | :--- |
| **[EXP-1](./EXP-1)** | DDL & DML Operations (CREATE, UPDATE, INSERT, DELETE) |
| **[EXP-2](./EXP-2)** | DQL, Aggregate Functions & Subqueries |
| **[EXP-3](./EXP-3)** | Advanced DQL & Constraints |
| **[EXP-4](./EXP-4)** | String Manipulation & Formatting |
| **[EXP-5](./EXP-5)** | Database Views |
| **[EXP-6](./EXP-6)** | SQL Joins (Inner, Outer, Equi) |
| **[EXP-7](./EXP-7)** | Set Operations & Complex Queries |
| **[EXP-8](./EXP-8)** | Correlated Subqueries & Exists |
| **[EXP-9](./EXP-9)** | TCL & Advanced Aggregation |
| **[EXP-10](./EXP-10)** | PL/SQL Basics |
| **[EXP-11](./EXP-11)** | PL/SQL Procedures |
| **[EXP-12](./EXP-12)** | PL/SQL Triggers |
| **[EXP-13](./EXP-13)** | Advanced Procedures & Functions |
| **[EXP-14](./EXP-14)** | Cursors in PL/SQL |
| **[EXP-15](./EXP-15)** | Comprehensive PL/SQL (Procedures, Views & Triggers) |
| **[EXP-16](./EXP-16)** | Database Management & Optimization |

*Note: The exact topics encompass standard lab curriculum elements complementing the verified modules.*

## 🛠️ Usage & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Mukilan-s18/DBMS-Experiments.git
   cd DBMS-Experiments
   ```

2. **Execute the scripts:**
   The scripts are written in standard SQL/PL-SQL and are meant to be executed in an Oracle Database environment (such as Oracle SQL Developer, SQL*Plus, or Oracle APEX).
   
   To run an experiment, open the respective file (e.g., `EXP-1`), copy the queries, and execute them in your database interface.

## 🚀 CI/CD & Integration

Since this repository primarily consists of static SQL scripts and lab experiments, standard CI/CD pipelines (like automated testing via GitHub Actions) are not inherently required. However, the repository can be integrated with tools like `sql-lint` for syntax checking or Flyway/Liquibase if automated schema migrations are adopted in the future.

---
*Built with a focus on comprehensive database management and structured query language mastery.*