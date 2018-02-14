list=['A','B','C','D','E','F','G','H','I','J','D','A','F','J','I','J','H','E','B','C']
i=['*','*','*','*','*','*','*','*','*','*','*','*','*','*','*','*','*','*','*','*']
x=list
c1=0
c2=0
while (x!=['*','*','*','*','*','*','*','*','*','*','*','*','*','*','*','*','*','*','*','*']):
    y=int(input('player 1 : '))
    z=int(input())
    i[y]=x[y]
    i[z]=x[z]
    print(i)
    if (x[y]==x[z]):
        x[y]='*'
        x[z]='*'
        c1=c1+1
    o=int(input('player 2 : '))
    p=int(input())

    i[o]=x[o]
    i[p]=x[p]
    print(i) 
    if(x[o]==x[p]):
         x[o]='*'
         x[p]='*'
         c2=c2+1

    print(c1,"-",c2)
if c1>c2:
    print("player 1 wins")
elif c2>c1:
    print("player 2 wins")
else:
    print("Draw")









    #set list=['A','B','C','D','E','F','G','H','I','J','D','A','F','J','I','J','H','E','B','C']
    #set i=['*','*','*','*','*','*','*','*','*','*','*','*','*','*','*','*','*','*','*','*']
    #set x=list
    #set c1=0  and c2=0
    
    #while x !=['*','*','*','*','*','*','*','*','*','*','*','*','*','*','*','*','*','*','*','*']
    # input y and z
    #  set  i[y]=x[y]
    #  set i[z]=x[z]
    #  set print(i)
    
    #if (x[y]==x[z]):
    #  set x[y]='*'
    #  set x[z]='*'
    #  set c1=c1+1
    #input o and p
    #i[o]=x[o]
    #i[p]=x[p]
    #print(i)
    
    #if(x[o]==x[p])
    #  x[o]='*'
    #  x[p]='*'
    #  c2=c2+1
    #print(c1,"-",c2
    
    #if c1>c2:
    #  print("player 1 wins")
    
    #else c2>c1:
    #  print("player 2 wins")
    
    #else:
    #  print("Draw")
    
