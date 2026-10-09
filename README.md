# AbleSpace QA Assignment

## Overview
This repository contains my QA testing submission for the AbleSpace staging application. Testing was performed using fictional test data and focused on core workflows, usability, and responsive behavior.

## Deliverables
- **Section 2 – Test Scenarios:** Exploratory testing scenarios and observed results.
- **Section 3 – Detailed Test Cases:** Test cases for creating, saving, searching, viewing, and editing a student.
- **Section 4 – Bug Reports:** Three detailed bug reports with reproduction steps and supporting evidence.
- **Section 5 – Cross-Browser and Responsive Testing:** Results from desktop browsers and responsive device emulation.
- **Section 6 – Test Summary:** Testing performed, key issues, limitations, and proposed next tests.

## Test Environment
- **Application:** `http://staging.ablespace.io`
- **Desktop browsers:** Google Chrome and Firefox
- **Responsive testing:** Chrome DevTools mobile emulation at 390 × 844; iPad Mini emulation using Chrome and Firefox
- **Test data:** Fictional data only

## Key Findings
Three detailed bugs were documented:
1. **BUG-01:** Continue button overlaps the IEP Creation feature card in the onboarding two-column layout.
2. **BUG-02:** Student search returns no results when the search term contains leading or trailing whitespace.
3. **BUG-03:** Refreshing View Data redirects the user to Caseload instead of retaining the current View Data context.

Additional responsive usability issues are documented in the cross-browser report.

## Scope and Limitations
- Actual mobile-app testing was not performed because the assignment did not identify a specific app or provide an app-store link.
- iPad Pro emulation was not tested.
- Security and load/performance testing were not performed.
- Destructive actions were intentionally avoided.
- No real student information was used.

## Repository Structure
Update the paths below to match the folders and filenames in this repository:

```text
AbleSpace-qa-assignment/
├── README.md
├── Section-2_Test-Scenarios/
│   └── Test_Scenarios.pdf
├── Section-3_Test-Cases/
│   └── Detailed_Test_Cases.pdf
├── Section-4_Bug-Reports/
│   ├── Bug_Reports.pdf
│   └── Evidence/
├── Section-5_Cross-Browser-Responsive/
│   └── Compatibility_Report.pdf
└── Section-6_Test-Summary/
    └── Test_Summary.pdf
```

## Next Testing Priorities
If additional testing time were available, I would test goal filters, the Take Data action in Caseload, search and filter combinations, data persistence and navigation, and complete iPad Pro responsive testing.

---
Prepared as a QA assignment submission for AbleSpace.
