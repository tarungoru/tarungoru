- 👋 Hi, I’m @tarungoru
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
tarungoru/tarungoru is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
""" code answers of telegram"""
""" sum of digits of given no. interms of negative"""
n=int(input())                                                
k=int(input())                                                  
t=int(input())                                                 
h=[]
s=[str(i).strip('-') for i in range(n,k-1,-1)]
for i in range(len(s)):
    if sum(list(map(int,s[i])))==-(t):
        h.append(-(int(s[i])))
print(h)
""" sum of digits of given no. interms of postive"""
n=int(input())
k=int(input())
t=int(input())
h=[]
s=[str(i) for i in range(n,k+1)]
for i in range(len(s)):
    if sum(list(map(int,s[i])))==t:
        h.append(int(s[i]))
print(h[0])
print(h[-1])
