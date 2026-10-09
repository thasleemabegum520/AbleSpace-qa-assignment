# AbleSpace QA Assignment

## Overview
This repository contains my QA testing submission for the AbleSpace staging application. Testing focused on core workflows, usability, and responsive behavior using fictional test data.

## Deliverables
- **Section 2 – Test Scenarios:** Exploratory test scenarios and observed results.
- **Section 3 – Detailed Test Cases:** Six test cases covering student creation, required-field validation, persistence after refresh, and editing student details.
- **Section 4 – Bug Reports:** Three detailed bug reports with reproduction steps and supporting screenshots included in the PDF.
- **Section 5 – Cross-Browser and Responsive Testing:** Results from desktop browser testing and responsive device emulation.
- **Section 6 – Test Summary:** Testing performed, key issues, limitations, and next testing priorities.

## Test Environment
- **Application:** `http://staging.ablespace.io`
- **Desktop browsers:** Google Chrome and Firefox
- **Responsive mobile testing:** Chrome DevTools at a viewport of 390 × 844
- **Tablet emulation:** iPad Mini using Chrome and Firefox
- **Test data:** Fictional data only

## Key Findings
Three detailed bugs were documented:
1. **BUG-01:** The Continue button overlaps the IEP Creation feature card in the onboarding two-column layout.
2. **BUG-02:** Student search returns no results when the search term contains leading or trailing whitespace.
3. **BUG-03:** Refreshing View Data redirects the user to Caseload instead of retaining the current View Data context.

Additional responsive usability issues are documented in the Section 5 report.

## Scope and Limitations
- Actual mobile-app testing was not performed because the assignment did not provide a specific application name or app-store link.
- iPad Pro emulation was not tested.
- Security and load/performance testing were not performed.
- Destructive actions were intentionally avoided.
- No real student information was used.

## Repository Structure
```text
AbleSpace-qa-assignment-main/
├── README.md
├── .gitignore
├── Section-2_Test-Scenarios/
│   └── Test_scenarios.pdf
├── Section-3_Test-Cases/
│   └── Test_Cases.pdf
├── Section-4_Bug-Reports/
│   └── Bug Reports.pdf
├── Section-5_Cross-Browser_Responsive-Testing/
│   └── Cross-Browser_Responsive_Testing.pdf
└── Section-6_Test-Summary/
    └── Test_summary.pdf
```

## Next Testing Priorities
With another 1–2 hours, I would test goal filters, the Take Data action in Caseload, search and filter combinations, data persistence and navigation, and iPad Pro responsiveness.

---
Prepared as a QA assignment submission for AbleSpace.
