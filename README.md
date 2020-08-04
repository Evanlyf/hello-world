# hello-world
def cmul(c):
    d = c.split(",")
    for i in d:
        global result
        result = result*int(i)
        
result = 1
cmul(input())
print(result)
