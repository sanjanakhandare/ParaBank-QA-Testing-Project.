ParaBank QA Testing Project

Manual QA testing project performed on ParaBank — a public demo banking application by Parasoft — to demonstrate end-to-end software testing skills as a fresher QA candidate.

Project Overview

This project covers the full manual testing lifecycle on a real, functioning banking application: test planning, test scenario and test case design, execution, and defect reporting with proper severity/priority classification. The project is being actively extended with API testing, SQL-based data validation, and automation.

Application under test: https://parabank.parasoft.com/parabank Modules tested: Registration, Login/Logout, Account Overview, Open New Account, Fund Transfer, Bill Pay, Update Contact Info

Project Timeline
April 2025 — Manual testing phase: test plan, test scenarios, test case design and execution, defect reporting
September 2026 — Project revisited and extended with API testing (Postman), SQL validation, and UI automation (Selenium/Playwright) — in progress
What's in this repo
File	Description
Test_Plan.docx	Scope, approach, environment, deliverables, entry/exit criteria
Test_Scenarios_and_Cases.xlsx	50 test scenarios and 32 fully executed test cases across 7 modules
Bug_Reports.xlsx	6 confirmed defects with steps to reproduce, severity, and priority
Screenshots/	Evidence for each confirmed defect
Summary of Results
32 test cases executed across Registration, Login/Logout, Account Overview, Open Account, Fund Transfer, and Update Contact Info
6 defects found (April 2025), re-verified in September 2026:
Fund transfer processed even when amount exceeds available balance (High) — Still Open
Fund transfer processed with $0 amount (Medium) — Still Open
Fund transfer succeeds with an invalid/non-existent source account (High) — No longer reproducible (the "From" field is now a dropdown restricted to valid accounts only)
Fund transfer allowed between the same account (Medium) — Still Open
Direct access to Account Overview after logout throws an internal error instead of redirecting to login (Low severity, Medium priority) — Still Open
Invalid phone number format accepted on Update Contact Info with no validation (High) — Still Open

All defects were re-tested against the live application in September 2026 to confirm current status before publishing this project. See Bug_Reports.xlsx for full re-verification notes.

Key Skills Demonstrated
Test Plan creation (scope, approach, entry/exit criteria)
Test scenario and test case design (positive, negative, and boundary cases)
Manual test execution and result documentation
Defect reporting with severity vs. priority classification
Bug reproduction with clear, repeatable steps
About Me

Sanjana Khandare — Fresher QA / Software Tester 
LinkedIn: https://www.linkedin.com/in/sanjana-khandare-2275a7266   
Email: sanjanakhandare321@gmail.com
