The placement is an essential part of B.Tech engineering. The performance in the placement is an essential task for all students as well as educational institutions. We have targeted this project to enhance the performance of students in the placement activity. To do so we have divided our project into two halves. First prediction of performance of student by analysing the existing data set of the student (result analysis). This activity includes, to predict the probability of an undergraduate student getting placed by applying different machine learning algorithms. 
In this system, we have used three different models to compare the same dataset namely K-Nearest Neighbours, Random Forest, XGBoost. We use parameters like age, gender, internship, CGPA, etc. to determine a student’s chances of getting placed. Then we move to finer details in the skillset of a student. We run the data through our algorithms chosen and derive conclusions as to what the student is lacking and help them improving their performance. 

The objective of this project is to increase the placement percentage of the institutions using Machine Learning Algorithms by analyzing previous year’s student’s historical data and predict placement possibilities of current students and aids 
To analyze the collected previous year’s students’ data for prediction of current year students in the institute.
To design a machine learning model to process the collected student’s academic data to predict the placement possibilities.
To imrprovize the proposed model and compare it with other traditional classification algorithms such as K-NN,  XGBoost, and Random forest with respect to the parameters like accuracy.

To enhance the possibilities of placement for current year students based on machine learning algorithm and designed model which is build-upon the previous years students’ academic data-analysis. 

Extracting result out of  dataset:
CGPA
Networking
Cloud computing
Web services
Data Analytics
Quality Assurance
AI                              
Internship
Quants
Logical Reasoning
Verbal
Programming

<img width="568" height="411" alt="image" src="https://github.com/user-attachments/assets/3c484951-0de7-4896-9480-5f6f77f00e6e" />


SOFTWARE: Jupyter Notebook
The pre existing LIBRARIES/ algorithms used for the implementation of this project are:-
Python
Numpy
Pandas
Matplotlib
Sklearn
Seaborn
K-NN
Random Forest
XGBoost

Random Forest:
A Random Forest Algorithm is a supervised machine learning algorithm which is extremely popular and is used for Classification and Regression problems in Machine Learning.
The following steps explain the working Random Forest Algorithm:
Step 1: Select random samples from a given data or training set.
Step 2: This algorithm will construct a decision tree for every 
training data.
Step 3: Voting will take place by averaging the decision tree.
Step 4: Finally, select the most voted prediction result as the final 
prediction result.
Strength – It is used in both classification and regression 
Weakness -It has more complexity

XGBoost:
XGBoost is a popular and efficient open-source implementation of the gradient boosted trees algorithm. Gradient boosting is a supervised learning algorithm, which attempts to accurately predict a target variable by combining the estimates of a set of simpler, weaker models.
The following steps explain the working Random Forest Algorithm:
Step 1: Make an Initial Prediction and Calculate Residuals
Step 2: Build an XGBoost Tree
Step 3: Prune the Tree
Step 4: Calculate the Output Values of Leaves
Step 5: Make New Predictions
Step 6: Calculate Residuals Using the New Predictions
Step 7: Repeat Steps 2–6

A graphical user interface (GUI) permits people to interact with electronic devices or programmes on computers through graphical elements such icons, buttons, menus, and windows rather than text-based interfaces. GUIs are designed to simplify and enhance the user’s interaction with the device or program by providing a more intuitive and user-friendly interface. 
GUIs are commonly used in modern operating systems such as Microsoft Windows, macOS, and Linux, as well as in applications such as web browsers, media players, and office productivity suites. They typically consist of graphical elements such as buttons, check boxes, sliders, drop-down menus, and texboxes, which users can click on, drag, or manipulate using a mouse or other input device. 
GUIs have a number of advantages over text-based interfaces, including ease of use, improved productivity, and increased user satisfaction. They also make it easier for non-technical users to interact with complex systems and programs, as they do not require specialized knowledge or training.

Model 1:
Parameters like CGPA and internship play a crucial role when we compare with other parameters like stream, age and gender. CGPA plays an important role as students having CGPA above 8 have higher placement rates. Students with more internship experience show a higher chance of getting placed. However, students belonging to streams like ECE, IT, CSE which have technical courses as a part of their curriculum have slightly more chances of getting placed.

Model 2 :
Internship percentage will increase if student is able to score higher in verbal, logical reasoning, quants and programming. Students who have more knowledge and score in these areas have a higher chance of getting an internship and finally securing placement. It can be concluded that students who have better CGPA and higher scores in subjects like (6 parametrs arrange) can achieve better placement rates.









