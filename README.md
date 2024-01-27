# PROJECTS

**Control effectiveness using Data Analytics
**
Objective: Develop a solution for automated evaluation of expense data to identify and report outliers against the expense policy in authorisation workflows using Data Analytics and automation. 

Implementation: We developed multiple automated checks which validate toxic combinations in expense data extracted from SAP Concur and report outliers. These outliers are further examined to identify any policy violation or potential fraud. We scheduled the analysis to automatically run periodically and provide a report to the key stakeholders which can further perform an RCA or design more controls. 

Tools Used: SAP Concur, Python, MS Excel, Power BI






**Continuous monitoring  of IT General Controls using Data Analytics**

Objective: Develop a solution which can extract data from various systems and perform testing of Change Management and Access Management controls daily and report the issues. 

Implementation: We extracted the population of changes and access requests with relevant attributes (change requester, change approver, deployment date or access granter, access termination date) from ITSM and HRMS tools. The ITGC controls were converted into mathematical rules and the datasets were analysed against these rules to produce exceptions. These exceptions were reported to the respective stakeholders to resolve potential audit issues. 

Tools Used: JIRA, Freshdesk, Python. Confluence

**Fraud detection in Refund systems using Data Analytics**

Objective: Identify the root cause of financial misstatement in refund systems by analysing the refund data along with testing application controls implemented to mitigate the risk. 

Implementation: We extracted the dataset of refunds provided to customers from the CRM and used data visualisation to identify the outliers. These outliers were used to identify the specific cases of control failure, which were remediation by changing the configuration of application controls according to the refund policy. 

Tools Used: PostgreSQL, Python, Matplotlib, MS Excel 

**Consolidated Risk Reporting using Data Visualisation**

Objective : Build a reporting dashboard which can extract, transform and visualise the key risk indicators (KRIs) corresponding to different type of enterprise risk. 

Implementation: We identified data sources for organisational risks such as operational risk, technology risk, regulatory risk, model risk, cyber risk and financial reporting risk. We defined KRIs corresponding to each risk category in Power BI and imported data from diverse sources like excel sheets, SQL database etc. Finally, we prepared a dashboard to visulise the KRIs and respective risk rating.

Tools Used: MS Excel, MS SQL, MS Power BI. 
