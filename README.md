# Student Performance Analysis

![Logo progetto](Docs/student_dataset-cover.jpg)

## Introduction

The academic performance of students is influenced by a combination of personal, social, and academic factors. Understanding these dynamics can help educators and institutions adopt targeted strategies to improve academic outcomes and student well-being. This project aims to analyze a dataset containing information on student grades and other potentially influencing factors, such as age, parental support, extracurricular activities, and absences.

### Project Objectives

The primary goal of this project is the application of machine learning techniques, particularly classification and clustering, to identify patterns and relationships in the data. Specifically, the project includes the following objectives:

- **Classification**: Development of predictive models capable of estimating students' performance classes based on the available variables.
- **Clustering**: Group students into meaningful clusters based on shared characteristics to identify common profiles of performance and behavior.
- **Interpretative Analysis**: Explore the factors that contribute most significantly to academic success, highlighting the relative importance of the variables included in the dataset.

By leveraging these techniques, the project aims to provide insights for a better understanding of student needs and the design of personalized educational interventions.

## Dataset Info

The dataset contains comprehensive information on 2,392 high school students, detailing their demographics, study habits, parental involvement, extracurricular activities, and academic performance. The target variable, `GradeClass`, classifies students' grades into distinct categories, providing a robust dataset for educational research, predictive modeling, and statistical analysis.

### Features

- **StudentID**: A unique identifier assigned to each student (1001 to 3392).
- **Age**: The age of the students ranges from 15 to 18 years.
- **Gender**: Gender of the students, where 0 represents Male and 1 represents Female.
- **Ethnicity**: The ethnicity of the students, coded as follows:
  - 0: Caucasian
  - 1: African American
  - 2: Asian
  - 3: Other
- **ParentalEducation**: The education level of the parents, coded as follows:
  - 0: None
  - 1: High School
  - 2: Some College
  - 3: Bachelor's
  - 4: Higher
- **StudyTimeWeekly**: Weekly study time in hours, ranging from 0 to 20.
- **Absences**: Number of absences during the school year, ranging from 0 to 30.
- **Tutoring**: Tutoring status, where 0 indicates No and 1 indicates Yes.
- **ParentalSupport**: The level of parental support, coded as follows:
  - 0: None
  - 1: Low
  - 2: Moderate
  - 3: High
  - 4: Very High
- **Extracurricular**: Participation in extracurricular activities, where 0 indicates No and 1 indicates Yes.
- **Sports**: Participation in sports, where 0 indicates No and 1 indicates Yes.
- **Music**: Participation in music activities, where 0 indicates No and 1 indicates Yes.
- **Volunteering**: Participation in volunteering, where 0 indicates No and 1 indicates Yes.
- **GPA**: Grade Point Average on a scale from 2.0 to 4.0, influenced by study habits, parental involvement, and extracurricular activities.

### Target Variable: GradeClass

- **GradeClass**: Classification of students' grades based on GPA:
  - 0: 'A' (GPA >= 3.5)
  - 1: 'B' (3.0 <= GPA < 3.5)
  - 2: 'C' (2.5 <= GPA < 3.0)
  - 3: 'D' (2.0 <= GPA < 2.5)
  - 4: 'F' (GPA < 2.0)

### Note
The files classificazione_with_GPA, classificazione_noGPA, and classificazione_noGPA_noABS contain, respectively, the classification performed using all features, the classification without the GPA feature, and the classification without the GPA and Absences features. We believe that including the GPA feature in the classification process is not meaningful, as it represents a continuous value directly correlated with the GradeClass variable, which is the classification class.

## Contributors
Luca Bellante
Giansimone Coccia
Laura Ferretti
