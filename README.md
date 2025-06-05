# 🎓 Student Performance Analysis

![Project Cover](Docs/student_dataset-cover.jpg)

---

## 📘 Introduction

The academic performance of students is influenced by a combination of **personal, social, and academic factors**.  
Understanding these dynamics can help educators and institutions adopt **targeted strategies** to improve academic outcomes and student well-being.

This project aims to analyze a dataset containing information on student grades and other potentially influencing factors, such as **age, parental support, extracurricular activities, and absences**.

---

### 🎯 Project Objectives

The main goal is the application of **machine learning techniques**—particularly **classification** and **clustering**—to identify patterns and relationships in the data.

#### Key Objectives:

- ✅ **Classification**  
  Develop predictive models to estimate students' performance classes based on available variables.

- 🔗 **Clustering**  
  Group students into meaningful clusters based on shared characteristics to identify common profiles of performance and behavior.

- 🧠 **Interpretative Analysis**  
  Explore which factors contribute most to academic success, highlighting the importance of each variable in the dataset.

> 💡 These insights will support a deeper understanding of student needs and the design of **personalized educational interventions**.

---

## 📊 Dataset Information

This dataset contains detailed information on **2,392 high school students**, covering demographics, study habits, parental involvement, extracurricular participation, and academic performance.

The **target variable**, `GradeClass`, categorizes student performance into grade classes, enabling robust **predictive modeling** and **educational research**.

---

### 📌 Features Description

| Feature              | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| `StudentID`          | Unique identifier assigned to each student (1001 to 3392)                   |
| `Age`                | Age of the student (15–18 years)                                            |
| `Gender`             | 0 = Male, 1 = Female                                                        |
| `Ethnicity`          | 0 = Caucasian, 1 = African American, 2 = Asian, 3 = Other                   |
| `ParentalEducation`  | 0 = None, 1 = High School, 2 = Some College, 3 = Bachelor's, 4 = Higher     |
| `StudyTimeWeekly`    | Weekly study time in hours (0–20)                                           |
| `Absences`           | Number of school-year absences (0–30)                                       |
| `Tutoring`           | 0 = No, 1 = Yes                                                             |
| `ParentalSupport`    | 0 = None, 1 = Low, 2 = Moderate, 3 = High, 4 = Very High                    |
| `Extracurricular`    | 0 = No, 1 = Yes                                                             |
| `Sports`             | 0 = No, 1 = Yes                                                             |
| `Music`              | 0 = No, 1 = Yes                                                             |
| `Volunteering`       | 0 = No, 1 = Yes                                                             |
| `GPA`                | Grade Point Average (scale: 2.0–4.0), influenced by study habits, etc.      |

---

### 🎯 Target Variable: `GradeClass`

Categorization of student performance based on GPA:

| Code | Grade | GPA Range          |
|------|-------|--------------------|
| 0    | A     | GPA ≥ 3.5          |
| 1    | B     | 3.0 ≤ GPA < 3.5    |
| 2    | C     | 2.5 ≤ GPA < 3.0    |
| 3    | D     | 2.0 ≤ GPA < 2.5    |
| 4    | F     | GPA < 2.0          |

---

### ⚠️ Note

The following files represent classification runs under different feature constraints:

- **`classificazione_with_GPA`**: Classification using all features  
- **`classificazione_noGPA`**: Classification without the `GPA` feature  
- **`classificazione_noGPA_noABS`**: Classification excluding both `GPA` and `Absences`

> Including the `GPA` feature in classification is not considered meaningful, as it is a **continuous value directly correlated** with the `GradeClass` target variable.

---

## 👥 Contributors

- **Luca Bellante**  
- **Giansimone Coccia**  
- **Laura Ferretti**

---

🎉 *Thank you for exploring our project!*
