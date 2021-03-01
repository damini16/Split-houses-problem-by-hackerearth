# Split-houses-problem-by-hackerearth
n=int(input())
if n>=1 and n<=20:
    per=input()
if "HH" in per:
    print("NO")
else:
    per = per.replace(".","B")
    print("YES")
    print(per)
