a)  a = 0                                           O(1)
    while (a < n * n * n):                          O(n)
      a = a + n * n                                 O(1)


if n = 1
while 0 < 1:
a = 1

loops ends after one run

if n = 2
while 0 < 8
a = 0 + 4
while 4<8
a = 4 + 4

loop ends after two runs

The time complexity of this problem is linear time because as n increases so does the number of operations

O(n)

---------------------------------------------------------------------------

b)  sum = 0                                           

    for i in range(n):                                 
      i += 1
      for j in range(i + 1, n):
        j += 1
        for k in range(j + 1, n):
          k += 1
          for l in range(k + 1, 10 + k):
            l += 1
            sum += 1

The time complexity of this problem is quadratic time

n = 1 : 10 steps
n = 2 : 13 steps
n = 3 : 19 steps
n = 4 : 28 steps
n = 5 : 70 steps

As the input n increased the number of operations greatly increased

O(n**2)

---------------------------------------------------------------------------------

c)  def bunnieEars(bunnies):
      if bunnies == 0:
        return 0

      return 2 + bunnyEars(bunnies-1)

The time complexity is O(n) because bunnies is decremented n-1 for every pass until we hit 0 then we will return

if n = 5
return 2 + bunnyears(5 - 1)
return 2 + bunnyears(4 - 1)
return 2 + bunnyears(3 - 1)
return 2 + bunnyears(2 - 1)
return 2 + bunnyears(1 - 1)

O(n)

----------------------------------------------------------------------------------





