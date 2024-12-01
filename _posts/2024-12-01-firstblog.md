---
title: "FIRST BLOG"
date: 2024-12-01
---

2024-12-01 07:15

Status : 

Tags : [[my notes]] [[software engineering]] [[STLC - Software Testing Life Cycle]]

# Test Execution

---
- *Test Execution is the phase where test cases are executed in the prepared test environment to validate the application’s functionality, identify defects, and ensure it meets the specified requirements.*

![[Pasted image 20241201071848.png]]

---
### Key Steps in Test Execution (as described)

1. **Test Execution**
    - The test team executes the prepared test cases and captures the actual results.
    - Each test case either **passes** (if the actual result matches the expected result) or **fails** (if it doesn't meet expectations).
    
2. **Defect Reporting**
    - If a test case fails due to a problem or issue in the application, it is logged as a **defect** in the defect tracking tool.
    - Each defect is categorized, prioritized, and assigned to the relevant development team for resolution.
    
3. **Defect Resolution**
    - The reported defects are analyzed, fixed, and reassigned back to the testing team for **retesting**.
    - This step ensures the problem has been resolved and does not impact the application.
    
4. **Regression Testing**
    - Regression testing is performed after defect fixes to ensure that new changes have not introduced additional issues or affected existing functionalities.
    - This step helps maintain overall application stability.
    
5. **User Acceptance Testing (UAT)**
    - In the final stage, the **business users** perform **User Acceptance Testing (UAT)** to validate that the application meets their requirements.
    - It ensures the application is ready for deployment and aligns with the business objectives.

---

### Deliverables of Test Execution

1. **Test Execution Report:** Documentation of passed and failed test cases, along with actual results.
2. **Defect Log:** A detailed list of reported defects with their statuses and resolutions.
3. **Regression Testing Report:** Confirmation that existing features remain intact after defect fixes.
4. **UAT Sign-Off:** Approval from business users indicating the application is ready for release.

---

### Why Test Execution Is Crucial?

- Ensures that the application works as intended and meets the defined requirements.
- Identifies and resolves defects, improving software quality.
- Provides confidence to stakeholders before deployment.
- Validates the readiness of the application for real-world use through UAT.

By following this structured approach, Test Execution helps identify gaps and ensures the delivery of a stable, functional, and user-accepted application.

---
# References

- [[Software Testing Life Cycle]]
- [[CHAPTER 03.pdf]]
- [[Test Case Development]]
