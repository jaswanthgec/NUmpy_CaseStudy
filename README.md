# Numpy_CaseStudy
This case study is about how we can install Anaconda and use Jupiter Notebook, as well as code in Jupiter Notebook with some libraries and modules such as Numpy.
# Program 1:
import numpy as np

#create a 1-dimensional array 

a=np.array([1, 2, 3, 4, 5]) #converting a list into an array 

print(a,'\n')

#create a 2-dimensional array 

b = np.array([[1, 2, 3], [4, 5, 6]]) #Multidimensional array

print(b,'\n')

#create an array of zeros 

c = np.zeros((3, 4)) #Zero matrix

print(c,'\n') 

#create an array of ones 
d = np.ones((2, 2)) #ones matrix
print(d) 

# Example Program 1:
import numpy as np

#create a 1-dimensional array 

a=np.array([1, 2, 3, 4, 5]) #converting a list into an array 

print(a,'\n')

#create a 2-dimensional array 

b = np.array([[11, 23, 35], [47, 59, 63]]) #Multidimensional array

print(b,'\n')

#create an array of zeros 

c = np.zeros((2, 6)) #Zero matrix

print(c,'\n') 

#create an array of ones 

d = np.ones((4, 5)) #ones matrix

print(d) 

# Program 2:
#add two arrays

a=np.array([1, 2, 3])

b=np.array([4, 5, 6])

c = a + b #adding two arrays so that every individual element in both arrays can be added

print(c,'\n')

#multiply two arrays.

d=np.array([[1, 2], [3, 4]]) 

e=np.array([[5, 6], [7, 8]])
f = d * e #Multiplying two arrays

print(f,'\n')

#Perform matrix multiplication

g=np.array([[1, 2], [3, 4]]) 
h=np.array([[5, 6], [7, 8]])

i=np.dot (g, h) #dot product of two arrays

print(i)

# Example Program 2:
#Add two arrays

a=np.array([15, 27, 39])

b=np.array([43, 54, 61])

c = a + b #adding two arrays so that every individual element in both arrays can be added

print(c,'\n')

#multiply two arrays.

d=np.array([[5, 6], [7, 8]]) 

e=np.array([[10, 12], [14, 16]])
f = d * e #Multiplying two arrays

print(f,'\n')

#perform matrix multiplication

g=np.array([[5, 6], [7, 8]]) 
h=np.array([[10, 12], [14, 16]])

i=np.dot (g, h) #dot product of two arrays

print(i)
