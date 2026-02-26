# Day-61-100-Days-challenge-in-cybersecurity-
# 🛡️ Day 61: SQL Injection (SQLi) Fundamentals

## 📋 Overview
On Day 61 of my #100DaysEthicalHacking challenge, I explored **SQL Injection (SQLi)**. This vulnerability occurs when an application fails to properly sanitize user input, allowing an attacker to interfere with the queries that an application makes to its database.

## 🔍 Key Concepts

### Vulnerable Entry Points
* **Login Forms:** Using logic bypasses like `' OR 1=1 --`.
* **Search Fields:** Injecting queries to extract unauthorized data.
* **URL Parameters:** Manipulating `GET` requests to alter database behavior.

### Types of SQLi
| Type | Description |
| :--- | :--- |
| **Union-Based** | Leverages the `UNION` operator to combine results from multiple tables. |
| **Error-Based** | Forces database errors to leak structural information. |
| **Blind (Inferential)** | Observes server responses (True/False) or time delays to reconstruct data. |

## 🚧 Mitigation Strategies
1. **Prepared Statements:** Using parameterized queries to separate code from data.
2. **Input Validation:** Implementing allow-lists for expected data types and formats.
3. **Principle of Least Privilege:** Restricting database account permissions to the minimum required.

---
[Check out my progress for Day 62! ->](./Day62.md)
