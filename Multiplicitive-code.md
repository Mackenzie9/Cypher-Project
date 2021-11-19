## I Wrote The Code For the Multiplicative Cipher, Which was Considerably Harder
#### I Ended Up Brute Forcing My Way Through It. It Doesn't Automatically Cipher and Decipher Like the Other Code


##### Sets Numbers to Their Intended Values:
*       a = 0
        b = 1
        c = 2
        d = 3
        e = 4
        f = 5
        g = 6
        h = 7
        i = 8
        j = 9
        k = 10
        l = 11
        m = 12
        n = 13
        o = 14
        p = 15
        q = 16
        r = 17
        s = 18
        t = 19
        u = 20
        v = 21
        w = 22
        x = 23
        y = 24
        z = 25

##### The Value I Used To Repeat The Program (True/False Works Too):
*       guu = 0
##### User Input
*       mod = int(input("Enter a mod number: "))

##### The Main Program. Runs the Program Through the Calculations for Each Letter (I'm Not Sure if the Math is Correct):
*     while guu == 0:
         if mod > 0:
            aa = (a * mod)%26
            bb = (b * mod)%26
            cc = (c * mod)%26
            dd = (d * mod)%26
            ee = (e * mod)%26
            ff = (f * mod)%26
            gg = (g * mod)%26
            hh = (h * mod)%26
            ii = (i * mod)%26
            jj = (j * mod)%26
            kk = (k * mod)%26
            ll = (l * mod)%26
            mm = (m * mod)%26
            nn = (n * mod)%26
            oo = (o * mod)%26
            pp = (p * mod)%26
            qq = (q * mod)%26
            rr = (r * mod)%26
            ss = (s * mod)%26
            tt = (t * mod)%26
            uu = (u * mod)%26
            vv = (v * mod)%26
            ww = (w * mod)%26
            xx = (x * mod)%26
            yy = (y * mod)%26
            zz = (z * mod)%26
##### Allows the Program to End:        
*        guu = 1
##### Asks the User For a Different Input if They Input Something Other Than a Integer:    
*     else:
        print("Try again.")
        mod = int(input("Enter a mod number: "))
        
         




##### Prints the Results by Adding the Numbers From the Calculations with 65. (The Unicode for Capital A is 65.):
*       print("a:" + chr(bb + 97))
        print("b:" + chr(bb + 97))
        print("c:" + chr(cc + 97))
        print("d:" + chr(dd + 97))
        print("e:" + chr(ee + 97))
        print("f:" + chr(ff + 97))
        print("g:" + chr(gg + 97))
        print("h:" + chr(hh + 97))
        print("i:" + chr(ii + 97))
        print("j:" + chr(jj + 97))
        print("k:" + chr(kk + 97))
        print("l:" + chr(ll + 97))
        print("m:" + chr(mm + 97))
        print("n:" + chr(nn + 97))
        print("o:" + chr(oo + 97))
        print("p:" + chr(pp + 97))
        print("q:" + chr(qq + 97))
        print("r:" + chr(rr + 97))
        print("s:" + chr(ss + 97))
        print("t:" + chr(tt + 97))
        print("u:" + chr(uu + 97))
        print("v:" + chr(vv + 97))
        print("w:" + chr(ww + 97))
        print("x:" + chr(xx + 97))
        print("y:" + chr(yy + 97))
        print("z:" + chr(zz + 97))
  
  
  
  
  
    
