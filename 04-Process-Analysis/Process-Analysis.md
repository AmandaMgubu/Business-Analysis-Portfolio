# Problem Identification technique

## Fishbone diagram
The fishbone diagram illustrates the underlying causes of a single headline issue: sluggish, frequently incorrect student registration. People, Process, Technology, Data, Policy/Compliance, and Communication are essential categories in this context; therefore, I organized the "bones" around them and then listed specific causes beneath each. For instance, I noted inconsistent master data and missing document standards under Data; fragmented SMS↔Finance↔CRM systems and no real-time APIs under Technology; single points of failure and limited cross-training under People; and duplicate checks and handoffs under Process. Creating this picture made it necessary for me and the stakeholders to distinguish between the causes (manual capture, integration gaps, confusing SOPs) and the symptoms (delays, rework, complaints).

### Please see Fishbone diagram attached

<img width="497" height="718" alt="Fishbone Diagram" src="https://github.com/user-attachments/assets/09bbcead-6885-479b-94ea-7315ed8ee8a1" />


## 5 WHYS Analysis Technique

Delays in registration turnaround times are the primary issue. This occurs because employees must process documents from different departments manually. Due to task duplication caused by the lack of integration between the CRM, Finance, and Student Management System, human labor is still required. The university's dependence on fragmented legacy systems that were never coordinated under a unified digital transformation plan is the cause of the lack of integration. Historically, IT and business groups operated independently, and leadership gave academic delivery precedence over increasing administrative effectiveness, which is why this strategy divide exists. Therefore, a strategic oversight is the deeper core cause: registration has been viewed as an administrative chore rather than a strategic process closely linked to long-term revenue, enrolment conversion, and student happiness.

1.	Why are registration turnaround times delayed?
•	Due to the manual processing of applications and supporting documentation across several departments

2.	Why are documents processed manually across departments?
•	Staff must re-enter and validate data independently because the CRM, Finance platform, and Student Management System (SMS) are not completely integrated.

3.	Why are the systems not integrated?
•	because the university lacks a comprehensive plan for digital transformation and instead depends on fragmented legacy platforms that were put into place at different times.

4.	Why was there no overarching digital transformation strategy?
•	Historically, business and IT departments have worked independently, and investment priorities have prioritized academic delivery over back-office process optimization.

5.	Why did investment priorities favour academic delivery over process optimisation?
•	Because leadership viewed registration as an administrative task rather than a strategic process that added value and directly influenced revenue, enrollment conversion, and student happiness.




# Problem prioritization technique

## Pareto Analysis
The Pareto chart ranks problems by their highest and lowest impact. It overlays a cumulative-percentage line, revealing which factors are responsible for most misery. I used case counts (the frequency of an issue) and time wasted (minutes/hours per instance) to calculate impact, which I then combined into a single "impact score." Three factors—manual processing, data integrity flaws, and system integration gaps—dominated the left side of the chart when I sorted these, contributing to almost 80% of all delays and rework. By automating document capture and validation, integrating SMS↔Finance↔CRM, and hardening master-data rules, I could concentrate improvement efforts on the essential few rather than distributing them widely. Additionally, Pareto provided me with a clear, defendable scope statement ("we will address the left-hand bars first") and baseline KPI targets (attack these three to reduce cycle time and rework).

### Please see Pareto diagram attached.

<img width="821" height="720" alt="Pareto Analysis" src="https://github.com/user-attachments/assets/55181c6d-53f7-4eb6-aeed-74545966d726" />
