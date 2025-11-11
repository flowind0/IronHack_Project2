# 🧩 Vanguard Digital Experiment — Module 2 Project

## 📘 Introduction

Welcome to the **Module 2 Project**!  
In this project, you will apply your skills in **data analysis, hypothesis testing, and visualization** to evaluate the results of a digital experiment.  
You will perform **EDA, performance analysis, hypothesis testing, experiment evaluation, and data visualization in Tableau**.

---

## 🏢 Project Context

You are a **Data Analyst** in the **Customer Experience (CX) team at Vanguard**, a U.S.-based investment management company.  

Your first assignment: analyze the results of a **digital experiment** designed to improve client experience.

### 🎯 The Digital Challenge

Vanguard wanted to test whether a **new, modern User Interface (UI)** — with **in-context prompts** (messages, hints, or cues) — could encourage **more clients to complete an online process** compared to the traditional design.

---

## 🧪 The Experiment

An **A/B test** was conducted to compare client behavior between two groups:

- **Control Group:** Clients using the *traditional online process*  
- **Test Group:** Clients using the *new UI design with in-context prompts*  

Both groups followed the same flow:
1. Initial page  
2. Three process steps  
3. Confirmation page (completion)

The main goal:  
➡️ Determine if the **new design** improves **completion rates** and **user experience**.

---

## 📊 Datasets

You will work with three datasets:

| Dataset | Description |
|----------|--------------|
| `df_final_demo` | Client demographic data (age, gender, account details, etc.) |
| `df_final_web_data_pt_1` & `df_final_web_data_pt_2` | Digital activity logs (should be merged before analysis) |
| `df_final_experiment_clients` | Information on which clients participated in the A/B test |

---

## 🧱 Metadata

These are the key variables used in the project:

| Column | Description |
|---------|--------------|
| `client_id` | Unique client ID |
| `variation` | Indicates experiment participation (control/test) |
| `visitor_id` | Unique client-device combination |
| `visit_id` | Unique session identifier |
| `process_step` | The digital process step visited |
| `date_time` | Timestamp of web activity |
| `clnt_tenure_yr` | Client tenure in years |
| `clnt_tenure_mnth` | Client tenure in months |
| `clnt_age` | Client’s age |
| `gendr` | Client’s gender |
| `num_accts` | Number of accounts held |
| `bal` | Total account balance |
| `calls_6_mnth` | Number of support calls in the last six months |
| `logons_6_mnth` | Number of logins in the last six months |

---

## 🗓️ Project Structure

### **1. EDA & Data Cleaning**
- Explore all datasets using **Pandas, Matplotlib, and Seaborn**
- Identify and fix data quality issues
- Perform **client demographic and behavior analysis**
  - Identify key client segments (age, tenure, balance, etc.)
  - Explore behavioral trends and process interactions

---

### **2. Performance Metrics**
Define and compute key performance indicators (KPIs):

- **Completion Rate:** % of users reaching the final confirmation step  
- **Time Spent per Step:** Average duration between steps  
- **Error Rate:** Frequency of users moving backward in the process  

Compare the performance of the **new design** vs. **traditional design** using these KPIs.

---

### **3. Hypothesis Testing**
Perform statistical testing to evaluate the redesign’s effectiveness:
- Test differences in completion rates between groups  
- Assess whether improvements are **statistically significant**  
- Optionally evaluate **cost-effectiveness thresholds**

---

### **4. Experiment Evaluation**
Evaluate the experiment from a design perspective:
- Was the design fair and balanced between groups?  
- Was the duration sufficient for reliable results?  
- What additional data could improve confidence in the findings?

---

### **5. Visualization (Tableau)**
Create an interactive **Tableau dashboard** that displays:
- Completion rates and group comparison  
- Demographic distribution  
- Time spent and error rates  
- Key insights and experiment outcomes  

---

### **6. Final Deliverables**
- Cleaned datasets  
- EDA and insights notebook  
- KPI analysis and hypothesis testing results  
- Experiment evaluation summary  
- Interactive Tableau dashboard  
- Final presentation and report  

---

## 🧰 Tools & Technologies

- **Python:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`  
- **Tableau:** for interactive dashboards and storytelling  
- **Kanban board:** for task management (Trello, Notion, or Jira)  
- **Optional:** Streamlit for additional dashboard interactivity  

---

## 👥 Collaboration

This is a **pair project**.  
Use a **Kanban board** to divide tasks efficiently and track progress.  
Suggested role split:
- **Analyst 1:** EDA, Data Cleaning, KPI Analysis  
- **Analyst 2:** Hypothesis Testing, Experiment Evaluation, Tableau Visualization  

---

## 🎓 Learning Outcomes

By completing this project, you will:
- Apply EDA and data cleaning techniques  
- Define and evaluate performance metrics  
- Conduct hypothesis testing on experiment data  
- Create visual and interactive dashboards in Tableau  
- Present clear, data-driven insights  

---

## 📦 Deliverables Checklist

- [ ] Cleaned data files  
- [ ] Python analysis notebooks  
- [ ] Tableau dashboard (.twbx)  
- [ ] Final presentation slides  
- [ ] `README.md` (this file)
