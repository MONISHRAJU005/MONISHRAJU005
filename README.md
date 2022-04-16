def mul(list_name):
    i=0
    mul_output=list_name[i]
    while i<len(list_name):
        mul_output*=list_name[i+1]
        if list_name[i+1]==list_name[-1]:
            break
        i+=1
    print(mul_output)
n=int(input("Enter here how many elements you want to add in your list:"))
list_name=[]
for i  in range(n):
    list_name.append(int(input("Enter an element to add in your list:")))
mul(list_name)
