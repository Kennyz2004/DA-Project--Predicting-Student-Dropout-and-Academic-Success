# Predicting Student Dropout and Academic Success 🌐
Linear Regression Model to predict student dropout rate.

Resources Used:
- [MDPI Article](https://www.mdpi.com/2306-5729/7/11/146)

# - What is the business problem? 
Qualification for scholarships in universities has to undergo criteria for the applicants that are committed to finishing their education and be considered an ideal investment to provide financial aid to education. The problem looks to understand factors that can cause students to drop out of a university and impact their academic outcomes.  The study in particular understands predictive factors that link to a student's dropout or completion by understanding what factors (course, mother/father occupation, displaced, age, gender, etc) interact with each other. With this research, it can safely predict the student dropout rate to improve the rate of student retention.

# - What is the business goal? 
This is significant to many universities, especially school administrators for scholarships, as they provide countless scholarship programs that depend on financial eligibility and academic performance. As scholarship programs are not given to every student who applies, we need to learn and predict students' backgrounds to effectively consider when looking out for higher-education scholarships. Scholarships are also considered to be an investment in a person's educational attainment, and if it can be predicted that a student could drop out from the program, discernment on their scholarship package can be adjusted.

# ML  used?:  
Given the supervised & structured nature of the dataset—that is, containing more than two class labels (i.e., “Graduate,” “Dropout,” and “Enrolled”)—multi-class classification should be used by the machine learning project to predict. Under this type of machine, we will be doing regression to predict the continuous value for our labels.


# Data processing
![Alt text](assets/3.png)

Dataset Column Descriptions

    Marital Status: The marital status of the student (e.g., single, married, divorced).

    Application Mode: Refers to the mode or type of application the student submitted to enroll in the course.

    Application Order: Indicates the order in which the student applied for the course. For example, whether it was the student’s first, second, or third choice.

    Course: The course or degree program the student is enrolled in (e.g., Computer Science, Engineering, etc.).

    Daytime/Evening Attendance: Specifies whether the student attends the course during the day or in the evening, representing their attendance schedule.

    Previous Qualification: The type of academic qualification the student had before enrolling in the course (e.g., high school diploma, vocational training).

    Previous Qualification (Grade): The final grade or score associated with the student's previous qualification.

    Nationality: The nationality of the student.

    Mother's Qualification: The highest academic qualification attained by the student's mother.

    Father's Qualification: The highest academic qualification attained by the student's father.

# Assumptions of the DataSet:
- The assumptions that we made for the data were that the 4300+ records of students' backgrounds and initial/later grades can represent a broader idea of student retention.
- Although the dataset only contains one semester's worth of data on grades/features/categories the scope of our study will focus on the retention of early dropout rates (to take on early interventions to improve retention rate)








