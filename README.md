#import pyttsx3
import pyttsx3
#-----------------------speaking code 1------------------------
engine=pyttsx3.init()
engine.setProperty("rate", 150)
voices = engine.getProperty("voices")
print("hi i'm a calculate ")
engine.say("hi i'm a calculate ")
print("_____________________________________________________________________")
print("if you want work with me just send this item to me %  *  +   /   -")
engine.say("if you want work with me just send this item to me")
print("_____________________________________________________________________")
print("if you dont want me just send me a Q")
engine.say("if you dont want me just send me a Q")
while True :
        engine.say("type this item to me")
        print("_____________________________________________________________________")
        print("type this item to me  %   *   +   /   -   q")
        engine.runAndWait()
#------------------codes(input)-----------------------------
        print("_____________________________________________________________________")
        your_type=str(input(" >>> "))
#-----------------codes(quit)------------------------------------
        if your_type=="q":
                print("ok bye :/")
#--------------------------speaking codes 0----------------------
                engine=pyttsx3.init()
                engine.setProperty("rate", 150)
                voices = engine.getProperty("voices")
                engine.say("ok bye")
                engine.runAndWait()
                break
#-----------------------------code(+)-----------------------------
        elif your_type=="+"  :
                engine=pyttsx3.init()
                engine.setProperty("rate", 150)
                voices = engine.getProperty("voices")
                engine.say("enter the first number")
                engine.runAndWait()
                first=float(input("enter the first number : "))
                engine=pyttsx3.init()
                engine.setProperty("rate", 150)
                voices = engine.getProperty("voices")
                engine.say("enter the second number")
                engine.runAndWait()
                second=float(input("enter the second number : "))
                mean=first+second
                print(mean)
#------------------------speaking code 2----------------------- 
                engine=pyttsx3.init()
                engine.setProperty("rate", 150)
                voices = engine.getProperty("voices")
                engine.say(mean)
                engine.runAndWait()
#-----------------------------codes(*)---------------------------------
        elif your_type=="*":
                engine=pyttsx3.init()
                engine.setProperty("rate", 150)
                voices = engine.getProperty("voices")
                engine.say("enter the first number")
                engine.runAndWait()
                first_1=float(input("enter the first number : "))
                engine=pyttsx3.init()
                engine.setProperty("rate", 150)
                voices = engine.getProperty("voices")
                engine.say("enter the second number")
                engine.runAndWait()
                second_1=float(input("enter the second number : "))
                mean1=first_1*second_1
                print(mean1) 
#---------------------------speaking code 3---------------------------
                engine=pyttsx3.init()
                engine.setProperty("rate", 150)
                voices = engine.getProperty("voices")
                engine.say(mean1)
                engine.runAndWait()
#-------------------------------codes(/)----------------------------------
        elif your_type=="/" :
                engine=pyttsx3.init()
                engine.setProperty("rate", 150)
                voices = engine.getProperty("voices")
                engine.say("enter the first number")
                engine.runAndWait()
                first_2=float(input("enter the first number : "))
                engine=pyttsx3.init()
                engine.setProperty("rate", 150)
                voices = engine.getProperty("voices")
                engine.say("enter the second number")
                engine.runAndWait()
                second_2=float(input("enter the second number : "))
                mean2=first_2/second_2
                print(mean2) 
#---------------------------speaking code 4---------------------------
                engine=pyttsx3.init()
                engine.setProperty("rate", 150)
                voices = engine.getProperty("voices")
                engine.say(mean2)
                engine.runAndWait()
#-------------------------------codes(-)----------------------------------
        elif your_type=="-" :
                engine=pyttsx3.init()
                engine.setProperty("rate", 150)
                voices = engine.getProperty("voices")
                engine.say("enter the first number")
                engine.runAndWait()
                first_3=float(input("enter the first number : "))
                engine=pyttsx3.init()
                engine.setProperty("rate", 150)
                voices = engine.getProperty("voices")
                engine.say("enter the second number")
                engine.runAndWait()
                second_3=float(input("enter the second number : "))
                mean3=first_3-second_3
                print(mean3) 
#-------------------------------speaking code 5-------------------------------
                engine=pyttsx3.init()
                engine.setProperty("rate", 150)
                voices = engine.getProperty("voices")
                engine.say(mean3)
                engine.runAndWait()
#-------------------------------codes(%)-----------------------------------
        elif your_type=="%":
                engine=pyttsx3.init()
                engine.setProperty("rate", 150)
                voices = engine.getProperty("voices")
                engine.say("enter the first number")
                engine.runAndWait()
                first_4=float(input("enter the first number : "))
                engine=pyttsx3.init()
                engine.setProperty("rate", 150)
                voices = engine.getProperty("voices")
                engine.say("enter the second number")
                engine.runAndWait()
                second_4=float(input("enter the second number : "))
                mean4=first_4%second_4
                print(mean4)
#-------------------------------speaking code 6-------------------------------
                engine=pyttsx3.init()
                engine.setProperty("rate", 150)
                voices = engine.getProperty("voices")
                engine.say(mean4)
                engine.runAndWait()
#-------------------------------codes(else)---------------------
        else:
                print("I dont understood it you just can wright this item to me  %   *  +   /   -   q !!!")
#--------------------------------speaking codes 7-----------------
                engine=pyttsx3.init()
                engine.setProperty("rate", 150)
                voices = engine.getProperty("voices")
                engine.say("I dont understood it you just can wright this item to me ...")
                engine.runAndWait()














