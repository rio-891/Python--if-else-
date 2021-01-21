# Python--if-else-
If else example problem.

Hacker rank 2nd problem.
Task:-

Given an integer, , perform the following conditional actions:

If n is odd, print Weird
If n is even and in the inclusive range of 2 to 5 , print Not Weird
If n is even and in the inclusive range of 6 to 20, print Weird
If n is even and greater than 20 , print Not Weird
#########################################################################


if n%2==1:
   print('Weird')

elif n>20 and n%2==0:
    print('Not Weird')

elif n in range(6,21) and n%2==0 ##range 6,21 is taken because in question its qiven 6 20 but if we write 6,20 in program 20 will not be counted and will print Not weird.
    print('Weird')

elif n in range(2,5) and n%2==0:
    print('Not Weird')
