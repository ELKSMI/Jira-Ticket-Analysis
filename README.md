# Optimizing Support Workflow: A Data-Driven Analysis of Jira Tickets

![Jira Project Cover](https://github.com/ELKSMI/Jira-Ticket-Analysis/blob/main/cover.png)  <!-- Optional: Add a nice cover image -->

## 📄 Project Overview
This project performs an in-depth analysis of a production support Jira ticket dataset. The primary objective is to move beyond high-level metrics and use Natural Language Processing (NLP) to understand the *content* of the tickets. By clustering tickets into thematic groups, we can identify hidden bottlenecks and provide targeted, strategic recommendations to improve the support team's resolution rate and overall efficiency.

This project simulates a real-world scenario where a data analyst provides actionable insights to an Agile Project Manager or a Head of Support.

**🛠️ Tools Used:** Python, Pandas, Scikit-learn (NLP), Matplotlib, Seaborn, Google Colab.

---

## 🎯 The Business Problem
The initial analysis showed a concerning statistic: **42% of all support tickets remained unresolved**. The key business question was not just *that* tickets were failing, but **WHY**. Are certain teams underperforming? Are tickets too complex? Or is there a systemic issue in our workflow?

---

## 📈 The Analysis and Key Findings
I followed a structured data analysis workflow, from data cleaning and EDA to advanced NLP-based clustering. The analysis revealed a powerful insight that was not visible from surface-level data.

### Key Finding: The Bottleneck is "WHAT," not "Who"

The root cause of the high unresolved rate was not poor team performance, but a specific **knowledge gap** related to one category of issues.

![Evidence Chart](https://github.com/ELKSMI/Jira-Ticket-Analysis/blob/main/evidence_chart.png)  <!-- **IMPORTANT**: Upload your chart to the repo and link it here -->

As the chart clearly shows:
- ✅ **High Success Rate:** The team is highly effective at resolving most technical issues, including `Login Issues`, `Password Resets`, and `Data Maintenance`.
- ❌ **Critical Failure Point:** Nearly **100% of tickets related to "Payment Issues" remain unresolved**. This is the single biggest bottleneck in the entire support workflow.

---

## 🚀 Strategic Recommendations
Based on this core finding, I proposed a 3-step action plan to address the bottleneck and improve performance:

1.  **Triage the "Pending Investigation" Backlog:** Implement a specialized process to ensure all tickets are diagnosed and assigned within 24 hours.
2.  **Form an Expert Squad for Payment Issues:** Create a dedicated team of specialists to handle all complex payment-related tickets. This squad will develop expert knowledge and create playbooks to streamline resolution.
3.  **Standardize and Delegate Solved Problems:** For the high-success categories, create simple Standard Operating Procedures (SOPs). This allows junior team members to handle them, freeing up senior staff to focus on the critical payment issues.

---

## 🔗 Connect with Me
Thank you for reviewing my project! I am passionate about using data to solve real-world business problems.

*   **LinkedIn:** (https://www.linkedin.com/in/aymane-el-kasmi/)
*   **Full Notebook:** You can view the complete Python code and step-by-step analysis in the [Jira_Ticket_Analysis.ipynb](link_to_your_notebook_file.ipynb) file in this repository.
