def gen_fib(num):
    a,b=0,1
    if num==0:
      return True
    if num==1:
      return True
    while True:
        c=a+b
        if c==num:
            return True
        if c>num:
            return False
        a=b
        b=c
num=int(input())
r=gen_fib(num)
print(r)
