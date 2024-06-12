# Survival-Duration-Calculator

It is a Python program to calculate the duration of how long a person lived based on his age.

Different time units:
   Months,
   Weeks ,
   Days,
   Hours
   Minutes
   Seconds

   Implementation :

   class User:
    def __init__(self,name):
        self.name = name
        
def survival_calci(user):
    print(f'''
            *****Welcome {user.name}, What's your age? *****
         ''')
    
    age=int(input())
    
    print(f'''
            Please choose time unit:
            Months
            Weeks
            Days
            Hours
            Minutes
            Seconds
            ''')
    print("Note: You can write the full name of the time unit.")
    choose=input()
    if choose=='Months':
        Months= (age)*12
        print("You lived for {} Months".format(Months))
        
    elif choose=='Weeks' :
        Weeks= ((age)*365)/7
        print("You lived for {} Weeks".format(Weeks))
        
    elif choose=='Days' :
        Days= (age)*(365)
        print("You lived for {} Days".format(Days))
        
    elif choose=='Hours':
        Hours=((age)*365)*24
        print("You lived for {} Hours".format(Hours))
        
    elif choose=='Minutes':
        Minutes= (((age)*365)*24)*60
        print("You lived for {} Minutes".format(Minutes))
        
    elif choose=='Seconds':
        Seconds= (((age)*365)*24)*60*60
        print("You lived for {} Seconds".format(Seconds))
        
    else:
        print("Incorrect Choice")
        
    return
 Driver code:
      Tejaswini=User('Tejaswini')
      survival_calci(Tejaswini)

  Output:

  *****Welcome Tejaswini, What's your age? *****
         
24

            Please choose time unit:
            Months
            Weeks
            Days
            Hours
            Minutes
            Seconds
            
Note: You can write the full name of the time unit.
Months
You lived for 288 Months

