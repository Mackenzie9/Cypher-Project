## I Wrote The Code For the Multiplicative Cipher

##### Sets Numbers to Their Intended Values:
*       a = 26
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
        run = True
##### User Input
*       mod = int(input("Enter a mod number: "))

##### The Main Program. Runs the Program Through the Calculations for Each Letter and Returns a Different Letter, One That Varies Depending on the Mod Number Input:
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
        
         




##### Changes the Numbers We Got From the Previous Calculations Into a List That Can be Used to Cipher and Decipher the Input:
*       aaa = (chr(aa + 97))
        bbb = (chr(bb + 97))
        ccc = (chr(cc + 97))
        ddd = (chr(dd + 97))
        eee = (chr(ee + 97))
        fff = (chr(ff + 97))
        ggg = (chr(gg + 97))
        hhh = (chr(hh + 97))
        iii = (chr(ii + 97))
        jjj = (chr(jj + 97))
        kkk = (chr(kk + 97))
        lll = (chr(ll + 97))
        mmm = (chr(mm + 97))
        nnn = (chr(nn + 97))
        ooo = (chr(oo + 97))
        ppp = (chr(pp + 97))
        qqq = (chr(qq + 97))
        rrr = (chr(rr + 97))
        sss = (chr(ss + 97))
        ttt = (chr(tt + 97))
        uuu = (chr(uu + 97))
        vvv = (chr(vv + 97))
        www = (chr(ww + 97))
        xxx = (chr(xx + 97))
        yyy = (chr(yy + 97))
        zzz = (chr(zz + 97))
        final = str(aaa + bbb + ccc + ddd + eee + fff + ggg + hhh + iii + jjj + kkk + lll + mmm + nnn + ooo + ppp + qqq + rrr + sss + ttt + uuu + vvv + www + xxx + yyy + zzz)
##### Asks Whether the User Wants to Cipher or Decipher the Input:
*       que = str(input("C for Cipher, D for Decipher: "))
##### Loops the Question if the Input is Not Valid:
*       while run == True:
##### The Code That Runs if the User Inputs "C". Ciphers the Input:
*       if que == "C":
            tra = str.maketrans("abcdefghijklmnopqrstuvwxyz", str(final))
            print(inpu.translate(tra))
            run = False
            break
##### The Code That Runs if the User Inputs "D". Deciphers the Input:  
*       if que == "D":
            art = str.maketrans(str(final), "abcdefghijklmnopqrstuvwxyz") 
            print(inpu.translate(art))
            run = False
            break  
##### The Code That Runs if the User Inputs Something Other Than "C" or "D". Loops the Question Until the Input is Valid:   
*       else:
            print("Try again.")
            que = str(input("C for Cipher, D for Decipher: "))
