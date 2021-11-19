## I Wrote The Code Below, Which Works Both as an Cipher and a Decipher.
##### The Translators: 
*     numbe = str.maketrans("abcdefghijklmnopqrstuvwxyz", "xyzabcdefghijklmnopqrstuvw") 
      apl = str.maketrans("xyzabcdefghijklmnopqrstuvw", "abcdefghijklmnopqrstuvwxyz")
##### The Code That Asks Whether The User Wants to Cipher or Decipher: 
*     choi = str(input("C for Decipher, D for Decipher: "))
##### The Variable I Used To Make the Code Repeat if the User Entered Something Other Than C or D (True and False Works Too): 
*     fin = 0
##### The Code That Runs If the User Chose C. Converts Every Letter to the Letter Three Spaces Before It (The Cipher): 
*        while fin == 0:    
            if choi == "C":
               sent = str(input("Write some letters: "))
               print("Your result: ")
               print(sent.translate(numbe))
               fin = 1
               break
##### The Code That Runs If the User Chose D. Converts Every Letter to the Letter Three Spaces After It (The Deipher):                
*        if choi == "D":
            digi = str(input("Write some letters: "))
               print("Your result: ")
               print(digi.translate(apl))
               fin = 1
               break
##### The Code that Runs if Neither C or D are Input. Makes the Program Run Again:     
*        if choi != "C" or choi != "D":
            print("Try again.")
            choi = str(input("C for Decipher, D for Decipher: "))
        

