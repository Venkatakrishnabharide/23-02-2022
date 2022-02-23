def reversed_list():
    rev=[]
    for i in l:
       l_popped=l.pop()
       rev.append(l_popped)
    return rev 
SAMPLE_LIST=[0,2,3,4]

print(reversed_list(SAMPLE_LIST))
