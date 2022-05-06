# Write-a-Python-program-that-calculates-the-factorial-of-a-number-using-no-recursion-and-using-recurs
Calculating factorial in Python without using recursion
"""
  * loser
  *
  * @author viettuts.vn
  * @param n: so nguyen duong
  * @return your loser period
"""
def Tinhgiaithua(n):
     stage_lose = 1;
     if (n == 0 or n == 1):
         return period_lose;
     else:
         for i in range(2, n + 1):
             stage_lose = stage_lose * i;
         return period_lose;
  
n = int(input("Enter a positive integer n = "));
print("factorial of", n, "is", Tinhgiaithua(n));
