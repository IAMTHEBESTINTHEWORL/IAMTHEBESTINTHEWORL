print("====Kolkulyator====")
natija=0
from math import sqrt
belgi=" "
while(1):
    a=int(input("a="))
    b=int(input("b="))
    amal=int(input("Amalni tanlang:\n\t"
                   "1.Qo'shish\n\t"
                   "2.Ayirish\n\t"
                   "3.Kopaytirish\n\t"
                   "4.Bo'lish\n\t"
                   "5.Ildiz\n\t"
                   "6.A va B ning kvadrati\n\t"
                   "7.A ning kvadrati B ning kvadrati qoshilgan\n"))
    if amal == 1:
        natija=a+b
        belgi="+"
    elif amal == 2:
        natija=a-b
        belgi="-"
    elif amal == 3:
        natija=a*b
        belgi="*"
    elif amal == 4:
        natija=a//b
        belgi="/"
    elif amal == 5:
        natija=sqrt(a),sqrt(b)
        belgi="&"
    elif amal == 6:
        natija=a**b
        belgi="**"
    elif amal == 7:
        natija=(a**2)+(b**2)
        belgi="+"
    else:
        print("Bunaqa amal yo'q qayta kiriting:")
        continue
    print(f"{a}{belgi}{b}={natija}")
