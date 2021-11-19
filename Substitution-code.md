## I Wrote The Code Below, Which Works Both as an Cipher and a Decipher.
##### The Translators: 
*     numbe = str.maketrans("abcdefghijklmnopqrstuvwxyz", "123456789!@#$%^&*-<>?:_{}|") 
      apl = str.maketrans("123456789!@#$%^&*-<>?:_{}|", "abcdefghijklmnopqrstuvwxyz")
##### The Code That Asks Whether The User Wants to Input Numbers or Letters: 
*     choi = str(input("L for letters, N for numbers: "))
##### The Variable I Used To Make the Code Repeat if the User Entered Something Other Than Y or N (True and False Works Too): 
*     fin = 0
##### The Code That Runs If the User Chose L. Converts Letters Into Numbers and Symbols (The Cipher): 
*        while fin == 0:    
            if choi == "L":
               sent = str(input("Write some letters: "))
               print("Your result: ")
               print(sent.translate(numbe))
               fin = 1
               break
##### The Code That Runs If the User Chose N. Converts Numbers and Symbols Into Letters (The Deipher):                
*        if choi == "N":
            digi = str(input("Write some numbers: "))
               print("Your result: ")
               print(digi.translate(apl))
               fin = 1
               break
##### The Code that Runs if Neither L or N are Input. Makes the Program Run Again:     
*        if choi != "L" or choi != "N":
            print("Try again.")
            choi = str(input("L for letters, N for numbers: "))
        

