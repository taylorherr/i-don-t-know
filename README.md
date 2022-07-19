# i-don-t-know
job = input("do you want to be warrior or defender?")
if job == "warrior":
    print("you have chosen warrior")
elif job == "defender":
    print("you have chosen defender")
else:
    print("unvalid input")
while job == "warrior":
    weapon = input("what is the weapon of your choice? Sword or Spear")
    if weapon == "Sword":
        print("you have chosen sword")
        break
    elif weapon == "Spear":
        print("you have chosen Spear")
        break
    else:
        print("that is an invalid statement")
while job == "defender":
    protect = input("who shall you protect? Princess or Queen")
    if protect == "Princess":
        print("You have chosen to protect the", protect)
    elif protect == "Queen":
        print("You have chosen to protect the", protect)
    else:
        print("unvalid statement")
    
