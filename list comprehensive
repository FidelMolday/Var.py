def f1(x): return x*2

def f2(x): return x*4

1st=[]
for i in range(16):
  1st.append(f1(f2(i)))
  
  
print(1st) 
print([f1(x)for x in range(64)if x in [f2(j)for j in range(16)]])
