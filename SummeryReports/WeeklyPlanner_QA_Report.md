# QA Structured Testing Project – Summary Report

## Project Overview
This project demonstrates structured manual QA testing using **TestRail** to manage and document test cases.  
The application under test was a custom workout-planning web app I developed, which allows users to add, edit, and remove workouts from a weekly planner and visualize training volume in a heatmap.  

The testing project highlights my ability to:
- Write clear and reproducible **test cases**.
- Define **preconditions, steps, and expected results**.
- Execute structured tests and record **results with evidence**.
- Identify and document **bugs** systematically.
- Use industry-standard QA tools (**TestRail**, **Jira**).

---

## Scope of Testing
The scope focused on three main functional areas:

1. **Weekly Planner**
   - Add workout  
   - Edit workout details (sets, reps, intensity, 1RM)  
   - Remove workout  
   - Calculate weight from 1RM  

2. **Heatmap Visualization**
   - Heatmap images load correctly  
   - Sets/week values update based on planner changes  
   - G-modified set calculations apply correctly  
   - Switching views (front, back, deep) updates data and images  

3. **G formula**
   - compound modification to weekly sets
   - Isolation modification to weekly sets
   - G threshold

---

## Tools Used
- **TestRail** – Structured test case management, execution tracking, and result logging  
- **Jira** – Bug tracking for failed results  

---

## Testing Approach
- **Structured Testing**: Each feature was broken down into detailed test cases with:  
  - Preconditions  
  - Test Steps  
  - Expected Results  
- **Execution**: Test runs were created in TestRail. Results were logged as *Pass* or *Fail*, with screenshots uploaded as supporting evidence.  
- **Bug Reporting**: Failed tests were documented in TestRail and cross-logged in Jira, including reproduction steps and screenshots.  

---

## Results Summary
- **Total Test Cases:** 12  
- **Passed:** 9  
- **Failed:** 3  
- **Bug Reports Filed:** 3  

### Key Issues Found
1. **Heatmap images not loading** – Images for muscle regions failed to render in some views  
2. **Global CNS counter not displayed** – Metric placeholder present, but no data surfaced  
3. **Fluff vs Hypertrophy box values** – Boxes displayed only raw sets; G-modified calculations were missing  

---

## Lessons Learned
- Maintaining **separation between raw metrics and formula-driven outputs** is essential to test coverage  
- Structured testing ensures clarity but requires discipline in defining reproducible steps  
- Evidence (screenshots + comments) strengthens the credibility of test results, especially for portfolio work  

---

## Next Steps
- Re-test after bug fixes are applied  
- Expand coverage to **exploratory testing** (planned as a second project using Jira)  
- Automate regression testing in the future using Selenium or Cypress to complement manual efforts  

---

✅ **This project demonstrates structured manual QA testing from planning through execution and bug reporting, using industry tools and a real application as the test subject.**

