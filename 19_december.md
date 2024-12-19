# Literature Review: Analysis of the Popularity of Process and Product Metrics for Quality Evaluation and Maintenance

## Overview
This literature review synthesizes key findings from academic works that explore the development, application, and validation of process and product metrics in software engineering. \nIt's just a draft btw

## Articles Reviewed

### 1. Object-Oriented Design Metrics as Quality Indicators (doi:10.1109/32.544352)
- **Metrics Discussed:**  
  - **Weighted Methods per Class (WMC):** Measures the complexity of a class by counting its methods. High values indicate potential maintenance issues.  
  - **Coupling Between Object Classes (CBO):** Tracks dependencies between classes. High coupling can lead to cascading failures during changes.  
  - **Lack of Cohesion on Methods (LCOM):** Highlights unrelated functions within a class, suggesting poor design.  

- **Key Insights:**  
  This study demonstrated that object-oriented metrics like WMC and CBO are effective predictors of fault-prone classes. These metrics are particularly valuable during the design phase as they highlight complexity and dependency issues early. The empirical validation showed that these metrics are better indicators of quality than traditional code metrics, such as lines of code (LOC). This supports the argument for using metrics that directly align with software architecture and maintainability goals.

---

### 2. Similarity Metrics for Business Process Models (doi:10.1016/j.is.2010.09.006)
- **Metrics Discussed:**  
  - **Node Matching Similarity:** Compares process model elements based on their labels.  
  - **Structural Similarity:** Evaluates the topology of process models.  
  - **Behavioral Similarity:** Analyzes the causal relationships between elements in a process.  

- **Key Insights:**  
  The research revealed that structural and behavioral metrics outperform simple text-based searches when assessing business process models. These metrics provide a deeper understanding of process interactions, making them essential for evaluating complex systems. Their ability to address both structure and behavior makes them valuable for quality evaluations, particularly in process optimization scenarios. This highlights how context-aware metrics often become more popular due to their practical applications in real-world scenarios.

---

### 3. Quality Metrics for Process Modelling (https://doi.org/10.3390/a16060295) 
- **Metrics Discussed:**  
  - **Behavioral Alignment Metrics:** Measures the consistency between process execution and intended design.  
  - **Structural Accuracy Metrics:** Assesses adherence to design principles and completeness.  
  - **Defect Density in Models:** Tracks issues within process modeling artifacts.
  - And very much more, really good article with many metrics in table. (but no so sure in its credibility)

- **Key Insights:**  
  This article demonstrates that combining structural and behavioral metrics provides better predictive capabilities for identifying process errors. Metrics like defect density and behavioral alignment are favored for their ability to pinpoint critical issues during modeling and design. Additionally, the study highlights that metrics integrated into tools (e.g., automated defect tracking) see greater adoption due to their ease of use and practicality.

---

## Application to Thesis
The reviewed articles provide critical insights into the popularity of specific metrics:  
1. **Practicality and Early Detection:** Metrics like WMC and CBO are popular because they highlight potential issues early, saving resources.  
2. **Contextual Relevance:** Structural and behavioral metrics demonstrate that metrics tailored to specific processes or contexts tend to gain broader adoption due to their actionable insights.  
3. **Balanced Approach:** Combining process and product metrics provides a well-rounded view of software quality, addressing both immediate and future needs.

These findings suggest that metric popularity is closely tied to their ability to address real-world challenges efficiently and effectively.

## Conclusion
The literature highlights the importance of using both process and product metrics in software quality and maintenance. Metrics that are easy to understand, actionable, and provide early warnings are often the most widely adopted. This review builds a foundation for further exploration in the thesis, focusing on why certain metrics are favored in practice and how they contribute to sustainable software development.
