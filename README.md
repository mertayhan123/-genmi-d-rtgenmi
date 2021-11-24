# -genmi-d-rtgenmi
a=(input("Üçgen ise 1 dörtgen ise 2 tuşlaması yapınız:"))
if(a=="2"):
    print("Lütfen dörtgenin kenarlarını sırayla giriniz")
    b=int(input())
    c=int(input())
    d=int(input())
    e=int(input())
    if(c==b and d==e and c==d):
        print("kare")
    else:
        print("dörtgen")
elif(a=="1"):
    print("Lütfen üçgenin kenarlarını sırayla giriniz")
    f=int(input())
    g=int(input())
    h=int(input())
    if(abs(f-g)<h<f+g):
        if(f==g and g==h):
            print("Eşkenar")
        elif((f==g and g!=h) or (f==h and h!=g) or (h==g and g!=f) ):
            print("İkizkenar")
        else:
            print ("Sıradan üçgen")
    else :
        print("Üçgen değil")
else:
    print("Geçersiz Sayı")
            
            
            
            
            
