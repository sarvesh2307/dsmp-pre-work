### Project Overview

 Student Management System


### Learnings from the project

 Use of Dictionary and Extracting values out of it


### Approach taken to solve the problem

 Simple and easy approach to write the code 


### Challenges faced

 I used lengthy way to pull values from dictionary. using for loop.
mathematics = {'Geoffrey Hinton' : 78,
               'Andrew Ng' : 95,
               'Sebastian Raschka' : 65,
               'Yoshua Benjio' : 50,
               'Hilary Mason' : 70,
               'Corinna cortes' : 66}

max_marks_scored = max(mathematics.values())
topper =[]
#print(max_marks_scored)

for i in mathematics:
    j=mathematics[i]
    if j==max_marks_scored:
        topper.append(i)
    
        break
print(topper[0])



### Additional pointers

 However I learned to use function to pull data from dictionary.

topper = max(mathematics,key = mathematics.get)
print(topper)



