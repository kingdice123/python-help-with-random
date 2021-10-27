# python-help-with-random
So, I'v been trying to make a new program.. I'm a newbie programmer so it can be a stupid question but I need help with my code
The main problem is that IDLE can run my code perfectly but when I open it like any other app (with double click), it just simply not work.. so I made an another code with the same way of using random and I got the same problem.
The first code:


    import random

    import time

    from pynput.keyboard import Key, Controller as Billkontroll

    import os

    Keyboard = Billkontroll()

    print("Válassz nehézségi szintet! 1-könnyű, 2-nehéz")

    fok = int(input())

    if fok == 1:

        hossz = 2
    
         for i in range(0, hossz):
    
              os.system('cls')
        
              print(random.randint(0, 99), end=" ")
        
             hossz += 1
        
         time.sleep(2)
    
    elif fok == 2:

        print("a")
    
    else:

        print("a")
    



This was the first code when I noticed this issue.
The second code is:




    import random

    import time

    import os

    a = int(input("Írd be a kód hosszát:\n"))

    os.system('CLS')

    print("A kód:")

    for i in range(0, a):

        print(random.randint(0, 9), end=" ")
    
    time.sleep(999)

    print("\n \n \n \n \n \n \n Bezárás: CTRL+C")







you can reach me on instagram: @ertelmetlen_cuccok, or later @boantufoe
