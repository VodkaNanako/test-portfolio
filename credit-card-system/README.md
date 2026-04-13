# Credit Card System Test Portfolio

## Project Overview
This portfolio presents the testing work for a personal credit card management system.  
The system supports card information display, bill-month switching, swipe, repayment, log rollback, and export functions, with a focus on business rule validation, result consistency, regression testing, and delivery quality.

## Tech Stack
`Spring Boot + MyBatis + SQLite + HTML/CSS/JavaScript`

## Core Business Focus
This project is suitable for demonstrating software testing capability because it involves more than basic CRUD logic. The key risks include:

- bill-month isolation
- amount linkage after swipe / repayment / rollback
- charge status switching and classification correctness
- export result completeness and path validity
- consistency across page display, API response, and database records
- regression verification based on real historical defects

## Portfolio Contents
This folder currently includes:

- `项目说明.md`
- `测试用例清单.md`
- `核心测试用例展开.md`
- `缺陷清单.md`
- `代表性缺陷详情.md`
- `回归测试清单.md`
- `接口测试与数据校验说明.md`
- `测试总结.md`

## Testing Highlights
The materials in this folder mainly demonstrate:

- test point analysis based on business rules
- test case design for core flows, abnormal scenarios, and boundary cases
- regression testing based on representative historical defects
- API verification with data consistency checks
- SQL-based validation across main table, log table, and status table
- structured test documentation output

## Notes
This repository contains desensitized test artifacts for portfolio presentation only.  
Source code, runtime configuration, and non-public data are not included.
