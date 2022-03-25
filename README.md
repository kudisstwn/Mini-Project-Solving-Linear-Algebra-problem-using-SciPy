# Mini-Project-Solving-Linear-Algebra-problem-using-SciPy

#import required libraries
import numpy as np
from scipy import  linalg

#Test has 30 questions and worth 150 marks
#True and false questions worth 4 marks each
#multiple choice questions worth 9 points each

#let x is the number of true/ false questions
#let y is the number of multiple choice questions

# (x + y = 30 )
# (4x + 9y = 150)
testQuestionVariable = np.array([[1,1],[4,9]])
testQuestionValue = np.array([30,150])

#use linalg function of Scipy 
#use solve method to solve the linear equation and find value for x and y
linalg.solve(testQuestionVariable,testQuestionValue)

