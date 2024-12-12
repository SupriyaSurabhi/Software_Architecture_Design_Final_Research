# Software_Architecture_Design_Final_Research
# Technical Debt and Architectural Decay: A Comparative Study in Microservices

## Overview
This repository contains the raw data, analysis scripts, and results for the research project **"Technical Debt and Architectural Decay: A Comparative Study in Microservices"**, conducted as part of the Software Architecture and Design course (CPSC 61200) at Lewis University.

This study explores the relationship between technical debt (TD) and architectural decay (AD) in software systems, focusing on monolithic and microservices architectures. It employs both quantitative analysis using CKMetrics and JDeodorant tools, and qualitative insights from case studies and developer interviews.


## Key Features
- **Repository Analysis**:
  - Six actively maintained GitHub repositories (three monolithic, three microservices) analyzed.
  - Focus on architectural migration and its effects on maintainability and scalability.

- **Quantitative Metrics**:
  - Object-oriented design metrics (LCOM, WMC, CBO) calculated using CKMetrics.
  - Code smells detected using JDeodorant.

- **Qualitative Insights**:
  - Case studies of prominent organizations like Netflix and Coca-Cola.
  - Developer and architect interviews providing practical perspectives.

---

## Research Questions
1. **What is the relationship between technical debt and architectural decay in microservices versus monolithic architectures?**
2. **How can object-oriented design metrics (LCOM, WMC, CBO) be used to quantify technical debt and architectural smells?**
3. **What are the long-term impacts of unmanaged technical debt and architectural decay on system performance, scalability, and maintainability?**

---

## Tools and Methodology
- **Repositories Analyzed**:
  - [Spring Petclinic Microservices](https://github.com/spring-petclinic/spring-petclinic-microservices)
  - [SiteWhere](https://github.com/sitewhere/sitewhere)
  - [Eventuate Tram Example](https://github.com/eventuate-tram/eventuate-tram-examples-customers-and-orders)
  - [Moduliths](https://github.com/moduliths/moduliths)

- **Metrics Computed**:
  - **LCOM** (Lack of Cohesion of Methods)
  - **WMC** (Weighted Methods per Class)
  - **CBO** (Coupling Between Objects)

- **Code Smell Detection**:
  - Tool: [JDeodorant](https://github.com/tsantalis/JDeodorant)

- **Developer Interviews**:
  - Insights from software architects and developers managing monolithic and microservices systems.

---

## Results
- **Monolithic Systems**:
  - Higher LCOM and WMC, indicating greater complexity and lower maintainability.
  - Common code smells: Blob Classes, Data Clumps, and God Classes.

- **Microservices Systems**:
  - Lower LCOM and WMC, but issues with inter-service dependencies.
  - Common code smells: Message Chains and Large Service.

---

## How to Use
1. **Data Analysis**:
   - Use scripts in the `scripts/` directory to reproduce metrics and visualizations.
   - Follow instructions in individual scripts for dependencies and execution.

2. **Reports**:
   - The final report is available in the `reports/` directory.
   - Case studies and interview insights can be found in the `references/` directory.

3. **Visualization**:
   - Use `visualization_tools.py` to generate trends and comparative graphs.

---

## References
1. [Technical Debt: From Metaphor to Theory and Practice](https://ieeexplore.ieee.org/document/6336920)
2. [CKMetrics GitHub](https://github.com/mauricioaniche/ck)
3. [JDeodorant GitHub](https://github.com/tsantalis/JDeodorant)
4. Additional references listed in the `final_report.pdf`

---

## Contact
For questions or collaboration, feel free to reach out:
- **Author**: Supriya Surabhi
- **Email**: SupriyaSurabhi@lewisu.edu
- **University**: Lewis University, Fall 2024
