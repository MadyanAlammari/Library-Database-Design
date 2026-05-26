# 📚 Library Database Design

> Relational database design for a university library management system — developed as a Database Systems course project at King Abdulaziz University.

## Overview
Full database design covering requirements analysis, ER diagram, schema mapping, normalization to 3NF, SQL implementation, and query development.

## What's Included
- Problem definition & business rules
- Entity-Relationship (ER) Diagram
- ER-to-Relational Schema Mapping
- Normalization: 1NF → 2NF → 3NF
- SQL table creation scripts (Oracle SQL)
- 5 queries + transactions
- Sample data (Appendix)

## Entities
`EMPLOYEE` `STUDENT` `BOOK` `LOAN` `GENRE` `BOOKSHELF` `SECTION` `LOAN_HISTORY` `AUTHORS_LIST` `SHIFT`

## Key Design Decisions
- 1:N between Student and Loan
- M:N between Loan and Book (resolved via LOAN_HISTORY)
- 1:1 between Employee and Section (manager)
- 3NF applied: decomposed SHIFT table to eliminate transitive dependency

## Tools
SQL Server · Oracle SQL · ERD Design

## Team
| Name | ID |
|------|----|
| Madyan Alammari | 2244530 |
| Yahya Salah | 2245434 |
| Khaled Salem | 2244524 |
| Abdulkarem Yahya | 2148850 |

**Supervisor:** Dr. Mohammed Al-twijri · King Abdulaziz University · Nov 2023
