# Recognize liars
Machine Learning allow us to recognize the behavior of a person trying to understand if he/she is lying. This simple Python program 
try to do this based on some characteristics identified by psychologists about the people who lie.


# What you need

Python: https://www.python.it/
Scikit-learn: http://scikit-learn.org/stable/

# Rules for a 20 minutes long talk
1) A liar move the head quickly (-1 to 1)
2) A liar breath harder (-1 to 1)
3) A liar use the hands to cover the throat (0 to 20)
4) A liar touch his/her mouth several times (0 to 20)
5) A liar doesn't pull up the foots (-1 to 1)
6) A liar point the finger several times (0 to 20) 
7) A liar doesn't blink a lot (0 to 720)
8) A liar sweat (-1 to 1)


# People

Most liar people: #0

[1,1,20,20,-1,20,0,1] 
[0.8, 0.9, 19, 16, -0.9, 500, 30, 0.9]  
[0.9, 0.8, 17, 19, -0.8, 600, 40, 0.7]   


Probably liars: #1

[0.7, 0.8, 18, 5, -0.5, 1, 50, 0.1]   
[0.5, 0.4, 17, 6, -0.4, 4, 100, 1]   
[0.3, 0.7, 7, 18, -0.7, 0, 150, 0.5]   
[0.8, 0.6, 6, 13, -0.8, 10, 200, 0.7]   
[0.9, 0.5, 4, 11, -0.1, 14, 150, 0.4]


Most honest people: #2

[-1,-1,0,0,1,0,360,-1]
[-0.9, -0.8, 2, 0, 1, 1, 355, -0.8]
[-1, -0.7, 1, 0, 1, 0, 385, 0]



Probably honest: #3

[-0.5, -0.4, 3, 0, 0.4, 2, 300, 0.8]
[-0.8, -0.3, 1, 3, 0.6, 1, 380, 1]
[-0.1, -0.4, 2, 2, 0.8, 1, 355, 0.4]
[0,    -0.2, 1, 1, 0.9, 0, 399, -0.3]
[-0.3, -0.8, 0, 0, 0.9, 0, 331, -0.4]
[-0.6, -0.9, 0, 1, 0.3, 0, 364, -0.8]
[-0.9, -0.1, 0, 3, 0.5, 4, 390, -0.9]


# Answers 

[0, 0, 0, 1, 1, 1, 1, 1, 2, 2, 2, 3, 3, 3, 3, 3, 3, 3]


