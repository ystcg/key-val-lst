def dict_fun(D):
    L=[]
    for k, v in D.items():
        s=k+v
        L.append(s)
    return L
n=int(input("Enter how many items:"))
Dict={}
for i in range(n):
        k=int(input("Enter key:"))
        v=int(input("Enter value:"))
        Dict[k]=v
print("The input dictionary is:",Dict)
List=dict_fun(Dict)
print("The output list is:",List)
