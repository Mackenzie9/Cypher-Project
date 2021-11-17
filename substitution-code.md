## I Wrote The Code Below, Which Works Both as an Encryptor and a Decipherer.
###### numbe = str.maketrans("abcdefghijklmnopqrstuvwxyz", "123456789!@#$%^&*-<>?:_{}|") 
###### apl = str.maketrans("123456789!@#$%^&*-<>?:_{}|", "abcdefghijklmnopqrstuvwxyz")
###### choi = str(input("L for letters, N for numbers: "))
###### fin = 0
###### while fin == 0:    
######     if choi == "L":
######         sent = str(input("Write some letters: "))
######         print("Your result: ")
######         print(sent.translate(numbe))
######         fin = 1
######         break
######     if choi == "N":
######         digi = str(input("Write some numbers: "))
######         print("Your result: ")
######         print(digi.translate(apl))
######         fin = 1
######        break
######     if choi != "L" or choi != "N":
######         print("Try again.")
######         choi = str(input("L for letters, N for numbers: "))
        

