# Unique Question identifier.<br>
![IIT Question Icon](https://github.com/Ajay-2007/mini-project/blob/master/Project%20Ideas/images/question_prediction.jpg)

Problem Definition</br>
	Motivation
		- <p>When we were JEE Aspirants, we used to buy a book on past 10 year question paper, practice
		paper etc. What we have seen so far is that they all contains the questions from last 10 years
		or even last 15 years.</p>
    <p>What if we can make a machine do this task for us so that we can have a question paper with full of question with greatest probability of coming up in the exam
		or a set of question paper from which the question with same or mixed up concepts will come up in the exam.
		</p>  
		<p>The motivation for us is to build an automated system which can perform this prediction accurately.
		In order to predict the pattern in a set of questions which may come in the next exam and so on.
		<br>
		And when the insitute is going to set a question paper for Test round they can 
		use our software to generate bunch of question with highest probability rate of coming into exam
		in this way student can benifit from the question and likely to ACE the final exam.


	Benifit
		-> Time reduction in problem setting
		-> greater probability of coming of the same question in Future
		-> Productivity of Teacher increases.

	Idea
		- We are going to select bunch of features from the question like
			- From which subject the problem is from e.g. Mathematics, Physics, Chemistry, Biology etc.
			- From wchih topic does the problem came from e.g. Trigonometry, SHM, Organic Chemistry etc.
			- In which category does the problem belong to.
			- Including three category for the problem e.g. Beginner, Intermidiate, Advanced.
			- In this way the problems can have many features which will lead to the good prediction 
			  and likelihood of coming in the exam or from the same concept.

		- Depending on the dataset we will choose and apply our Machine Learning Algorithms on the
		dataset using Clusting Algorithm and some optimization techniques.

		- After this a Graph Visualization showing the which year does the question came and what are
		the chances of coming the same question or question from the same concept again. 
    
Requirements

	Method
		- Clustring
		- NLP for semantic analysis
		- MLP (Mathematical Language Processing)

	Technology
		- Python
		- IBM NLP API
		- NLTK library for Natural Language Processing
		- D3.js for Data Visualization

	Dataset
		- Set of Questions MCQ/Subjective

Algorithms and Mathematics Used


	- Recurrent Neural Network
	- Applied Statistics
	- Probability (Bayes Theorems etc)

Output and Result


	- Problem sets consisting of questions with high probability of coming in the next exam.
