## I Wrote The Code For the Multiplicative Cipher, Which was Considerably Harder
#### I Ended Up Brute Forcing My Way Through It. It Doesn't Automatically Cipher and Decipher Like the Other Code


##### Sets Numbers to Their Intended Values
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

##### The Value I Used To Repeat The Program (True/Falso Works Too)
*       guu = 0
##### User Input
*       mod = int(input("Enter a mod number: "))

##### Main Program. Runs the Program Through the Calculations for Each Letter
*     while guu == 0:
         if mod > 0:
            aa = str(0)
            bb = round(b / mod + (b % mod))
            cc = round(c / mod + (c % mod))
            dd = round(d / mod + (d % mod))
            ee = round(e / mod + (e % mod))
            ff = round(f / mod + (f % mod))
            gg = round(g / mod + (g % mod))
            hh = round(h / mod + (h % mod))
            ii = round(i / mod + (i % mod))
            jj = round(j / mod + (j % mod))
            kk = round(k / mod + (k % mod))
            ll = round(l / mod + (l % mod))
            mm = round(m / mod + (m % mod))
            nn = round(n / mod + (n % mod))
            oo = round(o / mod + (o % mod))
            pp = round(p / mod + (p % mod))
            qq = round(q / mod + (q % mod))
            rr = round(r / mod + (r % mod))
            ss = round(s / mod + (s % mod))
            tt = round(t / mod + (t % mod))
            uu = round(u / mod + (u % mod))
            vv = round(v / mod + (v % mod))
            ww = round(w / mod + (w % mod))
            xx = round(x / mod + (x % mod))
            yy = round(y / mod + (y % mod))
            zz = round(z / mod + (z % mod))
##### Allows the Program to End        
*        guu = 1
##### Asks the User For a Different Input if They Input Something Other Than a Integer    
*     else:
        print("Try again.")
        mod = int(input("Enter a mod number: "))
        
         




##### Prints the Results by Adding the Numbers From the Calculations with 65. (The Unicode for Capital A is 65.)
*       print("a:" + "A")
        print("b:" + chr(bb + 65))
        print("c:" + chr(cc + 65))
        print("d:" + chr(dd + 65))
        print("e:" + chr(ee + 65))
        print("f:" + chr(ff + 65))
        print("g:" + chr(gg + 65))
        print("h:" + chr(hh + 65))
        print("i:" + chr(ii + 65))
        print("j:" + chr(jj + 65))
        print("k:" + chr(kk + 65))
        print("l:" + chr(ll + 65))
        print("m:" + chr(mm + 65))
        print("n:" + chr(nn + 65))
        print("o:" + chr(oo + 65))
        print("p:" + chr(pp + 65))
        print("q:" + chr(qq + 65))
        print("r:" + chr(rr + 65))
        print("s:" + chr(ss + 65))
        print("t:" + chr(tt + 65))
        print("u:" + chr(uu + 65))
        print("v:" + chr(vv + 65))
        print("w:" + chr(ww + 65))
        print("x:" + chr(xx + 65))
        print("y:" + chr(yy + 65))
        print("z:" + chr(zz + 65))
  
  
  
  
  
    
