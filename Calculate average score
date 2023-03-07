#Programmer: Ignashious Harrison
#Date: 2/24/2024
#Programmer Ignashious Harrison
#Declare variables
#weight=0
#count=0
#avgerage=0
#value=0
#sumw=0
#wsum=0
#main function
def main():
    i=0
    average = 0
    totalscore = 0
    sumw=0
    sum1=0
    while i<5:
        value=int(input("Enter your score: "))
        weight=float(input("Enter the weighted score: "))
        if weight>= 0:
            sumw = sumw + weight
            sum1 = sum1 + value * weight
            i +=1
        else:
          print("The score cannot be negative. Reinter score")
    average=CalculateAverage(sum1,sumw)
    PrintAverage(average)
    main()


#end of while
#calculate average
def CalculateAverage(sum1,sumw):
    average = sum1 / sumw
    return average
#end of function
#print average
def PrintAverage(average):
   
    print("Your average is: ",average)
    #end of function
main()
