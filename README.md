# 19-2-2022-2
def myprime(n):

    for i in range(2,n):

        if n%i==0:

            return False

    return True

 t=int(input())

 for i in range(t):

     n=int(input())

     c=0

     for i in range(2,n+1):

         if isprime(i):

             c=c+1

             print(c)
