Incoming Student Survey Analysis
Project Overview
This project analyzes survey data collected from incoming students at a Chicago-based university. The analysis focuses on understanding various factors that influence students' personal and academic experiences during their transition to university life. The survey data includes a variety of variables related to demographic information, academic self-management, social belonging, and student engagement. The aim is to assess how different student groups (e.g., Freshmen, Transfers, Athletes) compare to the overall student population in key areas.

Data Variables
Demographic Variables:
Meet 1+: Students who have met with one or more support groups (e.g., First-Generation, Pell-Eligible, SOC (Non-White)).
Meet 2+: Students who have attended events or meetings with two or more support groups.
Meet only 1: Students who have met with exactly one support group.
Meet only 2: Students who have met with exactly two support groups.
Meet all 3: Students who have attended meetings or events with three support groups.
None: Students who have not attended any meetings or events.
Gender: Student’s gender (e.g., Male, Female, Other).
Level Entry: Entry level of the student (e.g., Freshman, Transfer).
N-ETHNIC_GROUP_DESCR: Ethnicity of the student.
URM (Exc. Asian + White): Underrepresented minority (excluding Asian and White students).
SOC (Non-White): Students from non-white backgrounds.
Residential: Whether the student lives on campus or off-campus.
ACAD_GROUP: The academic group or department to which the student belongs.
Admit Type: Type of admission (e.g., Regular, Early Admission).
N-First Gen: Whether the student is a first-generation college student.
PELL: Whether the student is eligible for Pell Grants.
Maj Desc: Description of the student's major.
International: Whether the student is an international student.
Religion: The student’s religious affiliation (e.g., Catholic, Other Christian denominations, Islam, Judaism, Hinduism, Buddhism, Sikhism, None/Not Specified).
Latest Term Enrolled: The most recent term in which the student was enrolled.
Cumulative GPA: The student's cumulative GPA.
GPA Categories: Classification based on GPA (e.g., GPA < 2.5, 2.51 ≤ GPA < 3.00, 3 ≤ GPA < 3.5, GPA ≥ 3.5).
Enrolled in Winter: Whether the student is enrolled in the winter term.
Athlete: Whether the student is an athlete.
Currently Enrolled Hours: The number of credit hours the student is currently enrolled in.
Total Credits Earned: The total number of credits the student has earned.
Low BDE Scores - SA Intervention: Low scores in Behavioral and Developmental Evaluation requiring Student Affairs intervention.
Survey Index Variables:
ASM (Academic Self-Management): Measures organization, prioritization, seeking help, and incorporating feedback in academic settings.
PSM (Personal Self-Management): Measures organization, prioritization, seeking help, and feedback in personal goal settings.
AFF (Affinity to DePaul): Measures the student’s sense of belonging and pride in the institution.
BEL (Sense of Belonging): Assesses the student’s sense of community and acceptance within the university.
PRE (Personal Resiliency): Measures the student’s ability to overcome personal challenges and their belief in their ability to succeed.
SRE (Social Resiliency): Measures the student’s ability to rely on a supportive community for help when needed.
Hypotheses Tested
The following hypotheses are tested in this analysis:

H1: Freshmen students have lower academic self-management (ASM) scores compared to the overall student population.

Test: Compare the Academic Self-Management scores of Freshmen students to the overall population.
H2: Transfer students report higher sense of belonging (BEL) than Freshmen students.

Test: Compare the Sense of Belonging scores (BEL) between Transfer students and Freshmen.
H3: Athletes report higher levels of personal resiliency (PRE) than other student groups.

Test: Compare the Personal Resiliency (PRE) scores between Athletes and other student groups.
H4: Students who meet all three support groups (Meet all 3) have higher academic and personal self-management scores than those who do not attend any support group programs (Meet none).

Test: Compare the Academic Self-Management (ASM) and Personal Self-Management (PSM) scores between students who meet all three support groups and those who have attended none.
H5: First-generation students (N-First Gen) will report lower affinity to the university (AFF) compared to continuing-generation students.

Test: Compare the Affinity to the university (AFF) scores between first-generation and continuing-generation students.
H6: Pell-eligible students report lower sense of belonging (BEL) than non-Pell-eligible students.

Test: Compare the Sense of Belonging (BEL) scores between Pell-eligible and non-Pell-eligible students.
H7: Students enrolled in the Winter term will have higher levels of personal resiliency (PRE) compared to students who are not enrolled.

Test: Compare the Personal Resiliency (PRE) scores between students who are enrolled in the winter term and those who are not.
H8: Female students report higher social resiliency (SRE) scores than male students.

Test: Compare the Social Resiliency (SRE) scores between female and male students.
Analysis & Methodology
We used statistical techniques to test the hypotheses, including:

Descriptive Statistics: To summarize the dataset, including mean, standard deviation, and variance for the key survey indices.
t-Tests/ANOVA: To compare the means of different student categories (e.g., Freshmen vs. Overall) and determine if there are statistically significant differences.
Percent Deviation Analysis: To measure how each category deviates from the overall population in terms of percentage changes.
Visualizations: Radar charts, bar charts, and scatter plots to visually represent the differences between various groups.
How to Use This Repository
Clone the Repository: Download the project files using the following command:

bash
Copy
git clone https://github.com/username/project-name.git
Install Dependencies:

Install Python 3.x.
Install required libraries using pip:
bash
Copy
pip install -r requirements.txt
Run the Analysis:

Navigate to the analysis folder and run the Python scripts to generate the statistical analysis and visualizations.
View the Results:

The results of the analysis, including tables and charts, will be saved in the results/ folder.
Contributions
Feel free to contribute to this project by:

Reporting issues or bugs.
Suggesting improvements to the analysis.
Submitting pull requests with additional features or better visualizations.
License
This project is licensed under the MIT License.
