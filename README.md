logo ='''
88""Yb 8b    d8 88      dP""b8    db    88      dP""b8 88   88 88        db    888888  dP"Yb  88""Yb 
88__dP 88b  d88 88     dP   `"   dPYb   88     dP   `" 88   88 88       dPYb     88   dP   Yb 88__dP 
88""Yb 88YbdP88 88     Yb       dP__Yb  88  .o Yb      Y8   8P 88  .o  dP__Yb    88   Yb   dP 88"Yb  
88oodP 88 YY 88 88      YboodP dP""""Yb 88ood8  YboodP `YbodP' 88ood8 dP""""Yb   88    YbodP  88  Yb 
'''
print(logo)
body_weight = int(input("Enter your body weight: "))
body_height = int(input("Enter your height: ")) * 0.01
BMI = body_weight /(body_height**2)
print('%.2f' %BMI)
if 18.5 <= BMI <=25:
    print("Your are in healthy BMI range.")
elif BMI < 18.5:
    print ("Your are in unhealthy BMI range.")
else:
    print("Your are in overweight BMI range.")    
