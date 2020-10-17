# Project1
TOURISM
print("welcome to my tourism site")
print("please read all instructions carefully regarding world tour ")
import time as t
import webbrowser
t.sleep(2)
print("1. you have to select countries among these\n2. then enter your name\n3. we will contact you after verification")
c=input("enter your name")
t.sleep(2)
print("verification is completed")
print("we provide tourist services in these countries\n1. INDIA\n2. MEXICO\n3. SWITZERLAND")
t.sleep(3)
a=input("enter your selected country name")
if(a=='INDIA'):
    print("you selected {} for tourism purpose".format(a))
    print("most visiting states for tourism in {} are:\n1. GOA\n2. DELHI\n3 RAJASTHAN".format(a))
    t.sleep(3)
    b=input("enter your state which one u like")
    if(b=='GOA'):
        print("you selected {} for visiting these beautiful places".format(b))
        print(" places for visit in {} are:\n1. BAGA BEACH\n2. MARGAO CHURCH\n3. DIVAR ISLAND".format(b))
        t.sleep(3)
        print(webbrowser.open_new_tab('https://www.google.com/travel/guide/compare?q=goa+visiting+places&rlz=1C1CHBD_enIN922IN922&oq=goa+visiting+places&aqs=chrome.0.69i59j0l2j0i22i30l5.5530j0j15&sourceid=chrome&ie=UTF-8&dest_mid=/m/01c1nm&dest_src=o&sa=X&ved=2ahUKEwj4haKxrLfsAhWw63MBHcQJCTEQ6tEBKAQwAHoECAYQHw'))
    elif(b=='DELHI'):
        print("you selected {} for visiting these beautiful places".format(b))
        print(" places for visit in {} are:\n1. RED FORT\n2. INDIA GATE\n3. QUTAB MINAR".format(b))
        t.sleep(3)
        print(webbrowser.open_new_tab('https://www.tripsavvy.com/top-delhi-attractions-and-places-to-visit-1539209'))
    elif(b=='RAJASTHAN'):
        print("you selected {} for visiting these beautiful places".format(b))
        print("places for visit in {} are:\n1. JAIPUR\n2. UDAIPUR\n3. JODHPUR".format(b))
        t.sleep(3)
        print(webbrowser.open_new_tab('https://www.google.com/travel/guide/compare?q=rajasthan+visiting+places&rlz=1C1CHBD_enIN922IN922&oq=rajasthan+visiting+places&aqs=chrome..69i57j0j0i22i30l6.7801j0j15&sourceid=chrome&ie=UTF-8&dest_mid=/m/06k5_&dest_src=o&sa=X&ved=2ahUKEwik1bO8s7fsAhWEheYKHRnYDwUQ6tEBKAQwAHoECAoQCw'))
    else:
        print("not in the service list")
elif(a=='MEXICO'):
        print("you selected {} for tourism purpose".format(a))
        print("most visiting states for tourism in {} are:\n1. COLIMA\n2. JALISCO\n3. MORELOS".format(a))
        t.sleep(3)
        b=input("enter your state which one u like")
        if(b=='COLIMA'):
            print("you selected {} for visiting these beautiful places".format(b))
            print(" places for visit in {} are:\n1. EL CENTRO\n2. MALECON\n3. VOLCANO OF COLIMA".format(b))
            t.sleep(3)
            print(webbrowser.open_new_tab('https://www.tripadvisor.in/Attractions-g1575478-Activities-Colima_Pacific_Coast.html'))
        elif(b=='JALISCO'):
            print("you selected {} for visiting these beautiful places".format(b))
            print(" places for visit in {} are:\n1. MALECON BOARDWALK\n2. LAKE CHAPALA\n3. BUCERIAS".format(b))
            t.sleep(3)
            print(webbrowser.open_new_tab('https://www.tripadvisor.in/Attractions-g1575477-Activities-Jalisco.html'))
        elif(b=='MORELOS'):
            print("you selected {} for visiting these beautiful places".format(b))
            print(" places for visit in {} are:\n1. ROBERT BRADY MUSEUM\n2. TEPOZTECO\n3. PLAYA LA VIRGEN".format(b))
            t.sleep(3)
            print(webbrowser.open_new_tab('https://www.tripadvisor.in/Attractions-g1575498-Activities-Morelos_Central_Mexico_and_Gulf_Coast.html'))
        else:
            print("{} not in the service list.".format(b))
elif(a=='SWITZERLAND'):
    print("you selected {} for tourism purpose".format(a))
    print("most visiting states for tourism in {} are:\n1. ZUG\n2. VAUD\n3. URI".format(a))
    t.sleep(3)
    b=input("enter your state which one u like")
    if(b=='ZUG'):
        print("you selected {} for visiting these beautiful places".format(b))
        print("places for visit in {} are:\n1. ZYTTURN CLOCKTOWER\n2. MUSEUM BURG\n3. STRANDBAD".format(b))
        t.sleep(3)
        print(webbrowser.open_new_tab('https://www.tripadvisor.in/Attractions-g188110-Activities-Zug.html'))
    elif(b=='VAUD'):
        print("you selected {} for visiting these beautiful places".format(b))
        print("places for visit in {} are:\n1. OLYMPIC MUSEUM\n2. QUEEN STUDIO\n3. GOLDEN PASS LINE".format(b))
        t.sleep(3)
        print(webbrowser.open_new_tab('https://www.tripadvisor.in/Attractions-g188106-Activities-Canton_of_Vaud.html'))
    elif(b=='URI'):
        print("you selected {} for visiting these beautiful places".format(b))
        print("places for visit in {} are:\n1. SWISS PATH\n2. RUETLI\n3. BASECAMP".format(b))
        t.sleep(3)
        print(webbrowser.open_new_tab('https://www.tripadvisor.in/Attractions-g188104-Activities-Canton_of_Uri_Swiss_Alps.html'))
    else:
        print("{} not in the service list")    
else:
    print("{} not in the service list.".format(a))

