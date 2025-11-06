# E-commerce Recommendation Engine: A Business Analyst Portfolio Project

Elevator Pitch: This is an end-to-end portfolio project demonstrating the complete Business Analyst lifecycle. I identified that a major e-commerce platform was suffering from Low Average Order Value (AOV) due to poor product discovery.

I managed the project from the initial BRD and stakeholder analysis to the final technical execution. This involved designing the solution's architecture (BPMN & UML), writing the Agile User Stories, and building the core recommendation logic by analyzing 500,000+ real-world transactions in Python.

The final A/B test simulation, visualized in a Tableau dashboard, proved the project was a major success, resulting in a +6.29% lift in AOV and a +4.84% lift in Conversion Rate.

Final Result: The "Proof of Value" Dashboard

This Tableau dashboard was the final artifact, proving the project successfully beat its 5% AOV goal.

## Project Artifacts Repository

#### This repository contains all 11 professional artifacts created for this project, organized by phase.

Phase 1: Initiation & Scoping (The "Why")

01_Project_Vision_BRD.pdf

01_Stakeholder_Matrix.pdf

Phase 2: Analysis & Planning (The "How")

02_BPMN_As_Is_Process.png

02_BPMN_To_Be_Process.png

02_UML_Use_Case_Diagram.png

02_FRS_Functional_Requirements.pdf

02_Product_Backlog_User_Stories.csv

02_RTM_Traceability_Matrix.xlsx

Phase 3: Technical Analysis (The "Engine")

03_Market_Basket_Analysis.ipynb

Phase 4 & 5: Validation & Visualization (The "Proof")

04_AB_Test_Simulated_Data.xlsx

05_Tableau_Dashboard_Results.png

Phase 6: Final Presentation

06_Final_Project_Presentation.pdf

## Project Story & Methodology

#### This project followed a 6-phase process, moving from a high-level business problem to a proven, data-driven solution.

Phase 1: The Business Problem

The project began by identifying a core business problem (from the BRD): the e-commerce platform's revenue was suffering from a Low Average Order Value (AOV). My stakeholder analysis (Stakeholder_Matrix.pdf) confirmed the E-commerce Manager was accountable for this KPI and the primary sponsor.

Project Goal: To increase AOV by 5% within six months.

Phase 2: Analysis & Solution Design

I first mapped the "As-Is" (Problem) Process to visually identify why AOV was low. The diagram showed zero opportunities for product discovery in the checkout flow.

Next, I designed the "To-Be" (Solution) Process. This new flow strategically inserted three new recommendation features (FR-1, FR-2, FR-3) to create new cross-sell opportunities, directly solving the AOV problem.

These requirements were formally documented in a FRS and translated into an Agile Product Backlog with 20+ specific, testable Acceptance Criteria. Finally, an RTM was created to trace all requirements to their test cases.

Phase 3: The Technical "Engine"

To power the FR-3: "Customers Also Bought" feature, I performed a technical analysis on 541,000+ real transactions from the UCI Online Retail dataset.

Using Python, Pandas (for data cleaning), and the mlxtend library (for the Apriori algorithm), I successfully built the "brain" of the recommendation engine. This analysis produced a final table of high-confidence "IF...THEN..." rules (e.g., "IF a user buys 'RED TEACUP', THEN they are 76% likely to buy 'GREEN TEACUP'").

Phase 4 & 5: Proving the Business Value

With the logic built, I simulated an A/B test (ab_test_data.xlsx) to measure the feature's impact.

This data was loaded into Tableau to create the final KPI Dashboard. The results were a clear success, proving the project beat all goals and created significant business value.

AOV Lift (Primary Goal): +6.29% (Goal was +5%)

Conversion Rate Lift (Bonus Win): +4.84%

Phase 6: The Final Presentation

The entire project, from "Problem" to "Profit," was summarized in the 06_Final_Project_Presentation.pdf deck, which tells the complete story of how business analysis and data-driven solutions can create real-world revenue.

## Tools & Technologies Used

Business Analysis: BPMN, UML, User Stories, RTM, Agile & Waterfall Methodologies

Process Modeling: draw.io (with PlantUML)

Data Analysis: Python (Libraries: Pandas, mlxtend)

Data Visualization: Tableau

Documentation: Microsoft Excel, Microsoft Word, Microsoft Powerpoint, Google Colab
