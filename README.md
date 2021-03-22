# Triangle
Triangle with stars

num = int(input("Enter a number for Triangle\n"))
while(True):
    value= int(input("enter value 0 to 5\n0 Quit\n1 Right triangle\n2 Left Triangle\n3 Right Down triangle\n4 Left Down Triangle\n5 Center traingle\n6 Center Down traingle\n"))
    if value==1:
        print("Right triangle")
        for i in range(0,num+1):
            print("* "*i)
    elif value==3:
        print("Right Down triangle")
        for i in range(num,0,-1):
            print("* "*i)
    elif value==5:
        print("Center triangle")
        for i in range(0, num+1):
            print(" "*(num+1-i),"* "*i)
    elif value==2:
        print("Left triangle")
        for i in range(0,num+1):
            print(" "*(num-i)*2," *"*i)
    elif value==4:
        print("Left Down triangle")
        for i in range(num,0,-1):
            print(" "*(num-i)*2,"* "* i)
    elif value==6:
        print("Center down traingle")
        for i in range(num,0,-1):
            print(" "*(num-i),"* "*i)
    if value==0:
        break
