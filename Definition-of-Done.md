| No. | Level of Application | Category | Definition of Done Details | Notes |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Epic - Design | Data Model Design | Required entities, fields, and relationships are designed and reviewed. | |
| 2 | Epic - Design | System Architecture Design | Relevant context, container, and component diagrams are completed and reviewed. | |
| 3 | Epic - Design | System Architecture Design | Sequence diagrams show the main interactions and failure paths. | |
| 4 | Epic - Design | UI/UX Design | Required screens, interactions, and UI states are designed and reviewed. | |
| 5 | Epic - Design | Integration Design | Related API/message contracts are agreed with the receiving team. | Typed request/response structures and JSON examples. |
| 6 | Epic - Design | Integration Design | Access rules, errors, correlation, and retry behavior are defined where applicable. | |
| 7 | Issue - Development | Build | Coding is completed according to the reviewed design. | Code issues only. |
| 8 | Issue - Development | Code Quality | Lint checks pass without errors or warnings. | Code issues only. |
| 9 | Issue - Development | Security | No credentials or sensitive data are exposed in code, logs, or responses. | |
| 10 | Issue - Development | Security | Protected operations reject unauthorized access. | Where applicable. |
| 11 | Issue - Development | Accessibility | UI controls support keyboard interaction and readable labels. | Frontend issues. |
| 12 | Issue - Development | Responsiveness | The feature works correctly on the required desktop and mobile views. | Frontend issues. |
| 13 | Epic - Quality Verification | Performance | Performance checks meet the measurable limits defined for the feature. | Specify the operation, limit, and test conditions. |
| 14 | Issue - Testing | Unit Testing | Unit tests pass. | Code issues only. |
| 15 | Issue - Testing | Integration Testing | Integration/API tests and manual checks pass without runtime errors. | Where applicable. |
| 16 | Epic - Testing | End-to-end Testing | End-to-end tests pass for the complete feature flow. | |
| 17 | Issue - Review | Review | The reviewer approves the changes, and review feedback is resolved. | |
| 18 | Issue - Staging Merge | Merge | Changes merged into staging have passed review. | |
| 19 | Issue - Staging Merge | Post-merge Testing | Relevant tests pass after merging into staging. | |
| 20 | Issue - Dev Merge | Merge | Changes merged into dev have passed review and staging verification. | |
| 21 | Issue - Dev Merge | Post-merge Testing | Relevant tests pass after merging into dev. | |
| 22 | Team Integration - Internal | Integration | Frontend, backend, and supporting components work together through the agreed interfaces. | Within one team’s subsystem. |
| 23 | Team Integration - Internal | Testing | Integration and end-to-end tests pass after combining the components. | |
| 24 | Team Integration - Internal | Documentation | Related diagrams and documentation match the integrated implementation. | |
| 25 | Squad Integration - CP–PP | Integration | CP and PP work together using the agreed contracts. | Actual partner subsystems. |
| 26 | Squad Integration - CP–PP | Data Consistency | Both teams observe consistent data, statuses, and outcomes. | |
| 27 | Squad Integration - CP–PP | Testing | Joint integration and end-to-end tests pass. | |
| 28 | Squad Integration - CP–PP | Testing | Applicable authorization, failure, correlation, and retry checks pass. | |
| 29 | Squad Integration - CP–PP | Evidence | Joint test results and integration evidence are linked. | Include the tested versions. |
| 30 | Cross-squad Integration - PMS | Integration | Cross-platform workflows work through the shared PMS using the agreed contracts. | |
| 31 | Cross-squad Integration - PMS | Data & Access | Shared data, permissions, and subscription restrictions work across both ecosystems. | |
| 32 | Cross-squad Integration - PMS | Testing | Joint cross-platform integration and end-to-end tests pass. | |
| 33 | Cross-squad Integration - PMS | Testing | Failure and retry checks pass without incorrect duplicate actions. | |
| 34 | Cross-squad Integration - PMS | Evidence | Joint test results and integration evidence are linked. | Include the tested versions. |
| 35 | Epic - Main Merge | Merge | Changes merged into main have passed review, dev verification, and required integration checks. | |
| 36 | Epic - Main Merge | Post-merge Testing | Tests pass for the merged release version. | |
| 37 | Epic - Deployment | Deployment | The completed functionality is included in the target deployment environment. | |
| 38 | Epic - Deployment | Deployment | The deployed version starts successfully with its required configuration and dependencies. | |
| 39 | Epic - Deployment | Deployment Testing | End-to-end tests pass against the deployed version. | Include required partner workflows. |
| 40 | Issue - Documentation | Documentation | Related setup, API, or UI documentation is completed or updated. | According to the issue’s scope. |
| 41 | Issue - Documentation | Documentation | Test results and related pull requests are linked to the issue. | |
| 42 | Epic - Documentation | Documentation | The feature’s documentation issue is completed and linked. | |
| 43 | Epic - Documentation | Documentation | Data models and diagrams reflect relevant implementation changes. | |
| 44 | Epic - Documentation | Evidence | Child issues, pull requests, test results, and evidence are collected in the epic. | |
| 45 | Issue - Tracking | Issue Records | The issue has an assignee, reviewer, deadline, effort estimate, and checkbox DoD. | Assign the reviewer from the start. |
| 46 | Issue - Tracking | Issue Records | Dependencies, blockers, and status match the actual work. | |
| 47 | Issue - Tracking | Review Records | Reviewer feedback and its resolution are recorded. | |
| 48 | Issue / Epic - Bug Resolution | Bugs | Known bugs affecting the completed scope are resolved. | |
| 49 | Issue / Epic - Bug Resolution | Bugs | Critical and major bugs are prioritized before lower-severity bugs. | |
| 50 | Issue / Epic - Bug Resolution | Bugs | Bug fixes pass retesting. | |
| 51 | Issue / Epic - Bug Resolution | Bugs | No regressions are introduced in affected features. | |
| 52 | Issue - Sign-off | Sign-off | The reviewer confirms that the applicable DoD checks are satisfied. | |
| 53 | Epic - Sign-off | Sign-off | The feature works as intended without bugs. | |
| 54 | Epic - Sign-off | Sign-off | The team agrees that the feature is ready for demonstration or release. | |