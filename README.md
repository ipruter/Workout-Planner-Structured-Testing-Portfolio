# Workout Planner – Structured QA Testing (TestRail)

This project showcases **manual structured testing** performed in **TestRail** for the *Workout Planner App*.  
It demonstrates my ability to design, execute, and document structured test cases covering core functionality.  

---

## Project Overview
- **App Under Test**: Workout Planner (web-based fitness planner)  
- **Testing Type**: Manual Structured Testing  
- **Tool Used**: [TestRail](https://www.gurock.com/testrail/)  
- **Goal**: Validate core features of the Workout Planner through systematic test case design, execution, and defect documentation.  

---

## Key Features Tested

### Weekly Planner Module
1. **Add Workout to Day**  
2. **Edit Workout Details**  
3. **Remove Workout from Day**  
4. **1RM Entry and Weight Calculation**  
5. **Data Persistence Across Sessions**

### Growth Potential Formula (G)
- Validation of formula calculations for compound lifts and diminishing returns logic.  

---

## Test Case Design
Each test case in TestRail follows the same structured format:
- **Preconditions** – Initial state required before execution  
- **Steps** – Clear instructions for execution  
- **Expected Result** – Defined pass criteria  
- **Priority** – Criticality to core functionality  
- **Type** – Functional / Logic  

See full details in the [`TestCases/`](./TestCases) folder.

---

## Test Execution
Testing was executed in **TestRail** using **Test Runs**, where results were logged with:  
- **Pass / Fail status**  
- **Screenshots for evidence** (especially for failures)  
- **Comments on actual outcomes**  

 Execution records with screenshots are saved in the [`TestRuns/`](./TestRuns) folder.

---

## Sample Test Result
**Case:** Add Workout to Day  
- *Precondition*: No workout logged for Monday.  
- *Steps*: Select “Squats” from dropdown, assign to Monday.  
- *Expected Result*: Squats appear under Monday’s box.  
- *Outcome*: Passed (see screenshot in `TestRuns/Screenshots`).  

---

## Repository Structure
WorkoutPlanner-QA-Portfolio/
README.md # Project overview (this file)
- TestCases/ # Markdown files for individual test cases
- TestRuns/ # Markdown summaries of test runs
- Screenshots/ # Screenshot evidence from TestRail
- SummaryReports/ # High-level QA reports
