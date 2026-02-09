NIKUNJ DEEP UPADHYAY
25070123081
ENTC B1

THEORY-
Experiment 3 consist of tuple and its application of what tuple consist of first we introduce tuple as a variable with various data types, then indexing of tuple has been introduced as how can get to any value in a tuple indexing from left side start with 0 and from left side it start with -1.
If we had to get into a certain range in a tuple for example from x index to y index we had to get as output so range we had to declare as x:y+1 as of n range tuple gives output from 0 to n-1.
If we want a value in a tuple to be repeated we had to multiply it after using a comma to the value of how many times we want to repeat otherwise it will not give desired output.
There comes a difference between a tuple and a list that is tuples are immutable and list are mutable if we are adding any element to list then its id does not change but if we adding any element to tuple then its id changes. There are many operations we can do on tuple like calculating length by len functions and maximun, minimum value by max,min functions.
Count is a very special function we can use in a tuple to calculate how many times a value is occuring in a tuple.

ALGORITHM-
A=(A,G,K,J) declaration of a tuple
A[1]=G indexing in a tuple from left side start with o
A[-2]=K indexing from right side start with -1
A(0:3)=A,G,K range of tuple from 0 to n give values from 0 to n-1.
A=("s",)*2 multiplying element of tuple with the number of times we want to repeat a element.
print(A) results ("s","s")
A=(10)*5 
print(A) gives 50 so numbers always had to be in comma for it to be repeated
q=[g,j,k,l]
print("before id:" id(q)) results 234567
d=[f,]
q+=d
print(id(q)) results same as earlier 234567 so list are immutable
q=(g,j,k,l)
print("before id:" id(q)) results 234567
d=(f,)
q+=d
print("before id:" id(q)) results 234560 which changes so tuple are immuatable
q=(2,3,4,7)
len(q) results 4
max(q)=7
min(q)=2
sum(q)= 16 so various operations can be performed on a tuple.
s=("P","A","P","A","P")
a=s.count(P) gives 3
b=s.count(A) gives 2
count function used to count a variable in tuple.

CONCLUSION-
Study of tuple and its application with differnce from list.





