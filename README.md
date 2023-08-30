# Maximise-the-tastiness
# cook your dish here
for i in range (int(input())):
    a,b,c,d = map(int,input().split())
    p = max(a,b)
    q = max(c,d)
    print(p+q)
