print("NOTE! WE ARE OFFERING 50% OF FOR CHILDREN UNDER 10")
print("HOW MANY ADULTS ARE TRAVELLING:")
adults_traveling = int(input())
print("HOW MANY CHILDREN ARE TRAVELING:")
children_traveling = int(input())
print("PLEASE ENTER HOW WOULD YOU LIKE TO TRAVEL TO THE DESTINATION YOUR CHOOSE")
j=input("1:AIRPLANE 2:TRAIN 3:SHIP 4:BUS 5:CAR")
while children_traveling in children_traveling:
    if j == '1':
        adults_cost = adults_traveling * 200
        print("cost for adults is:", adults_cost)
        children_cost = children_traveling * 100
        print("cost for children is:", children_cost)
        break
    elif j=='2':
        adults_cost = adults_traveling * 150
        print("cost for adults is:", adults_cost)
        children_cost = children_traveling * 80
        print("cost for children is:", children_cost)
        break
    elif j == '3':
        adults_cost = adults_traveling * 120
        print("cost for adults is:", adults_cost)
        children_cost = children_traveling * 60
        print("cost for children is:", children_cost)
        break
    elif j == '4':
        adults_cost = adults_traveling * 100
        print("cost for adults is:", adults_cost)
        children_cost = children_traveling * 50
        print("cost for children is:", children_cost)
        break
    elif j == '5':
        adults_cost = adults_traveling * 80
        print("cost for adults is:", adults_cost)
        children_cost = children_traveling * 30
        print("cost for children is:", children_cost)
        break
    else:
        print("PLEASE ENTER CORRECT OPTION")
        break
