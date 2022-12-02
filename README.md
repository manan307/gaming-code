# Gaming-project
import random
import datetime
t_date=datetime.date.today()
t_time=datetime.datetime.now()
def swg():
    up=0
    cp=0
    for i in range (5):
        if up<3 and cp<3 or (cp==up):
            print(" ")
            print("_"*109)
            print(" ")
            print(" "*64,"ROUND",i+1,"".center(130))
            print(" ")
            print("1. SNAKE".center(130))
            print("2. WATER".center(130))
            print("3. GUN".center(130))
            print(" ")
            u=input("                                                            ENTER YOUR CHOICE :")
            print(" ")
            a=['SNAKE','WATER','GUN']
            b= random.randint(1,3)
            if (u=='1' and b==1) or (u=='2' and b==2) or (u=='3' and b==3):
                print(" "*64,"YOUR CHOICE :",a[int(u)-1])
                print(" "*64,"COMPUTER CHOICE :",a[b-1])
                print(" "*64,"DRAW")
                print(" "*64,"BOTH 1 POINT")
                cp+=1
                up+=1
                print(" "*64,"YOUR SCORE :",up)
                print(" "*64,"COMPUTER SCORE :",cp)
            elif (u=='1' and b==3) or (u=='2' and b==1) or (u=='3' and b==2):
                print(" "*64,"YOUR CHOICE :",a[int(u)-1])
                print(" "*64,"COMPUTER CHOICE :",a[b-1])
                print(" "*64,"YOU LOSE")
                cp+=1
                print(" "*64,"YOUR SCORE :",up)
                print(" "*64,"COMPUTER SCORE :",cp)
            elif (u=='3' and b==1) or (u=='1' or b==2) or (u=='2' and b==3):
                print(" "*64,"YOUR CHOICE :",a[int(u)-1])
                print(" "*64,"COMPUTER CHOICE :",a[b-1])
                print(" "*64,"YOU WIN")
                up+=1
                print(" "*64,"YOUR SCORE :",up)
                print(" "*64,"COMPUTER SCORE :",cp)
            else:
                print(" "*64,"Invalid Input")
                break
        elif cp==3:
            print(" ")
            print("_"*109)
            print(" ")
            print(" "*64,"YOU ARE LOOSER ")
            print(" ")
            print("_"*109)
            print(" ")
            break
        elif up==3:
            print(" ")
            print("_"*109)
            print(" ")
            print(" "*64,"YOU ARE WINNER ")
            print(" ")
            print("_"*109)
            print(" ")
            break
        else:
            print(" ")
            print("_"*109)
            print(" ")
            print(" "*64,"DRAW ")
            print(" ")
            print("_"*109)
            print(" ")
            break
def sps():
    up=0
    cp=0
    for i in range (5):
        if up<3 and cp<3 or (cp==up):
            print(" ")
            print("_"*109)
            print(" ")
            print(" "*64,"ROUND",i+1,"".center(130))
            print(" ")
            print("1. STONE".center(130))
            print("2. PAPER".center(130))
            print("3. SCISSOR".center(130))
            print(" ")
            u=input("                                                            ENTER YOUR CHOICE :")
            print(" ")
            a=['STONE','PAPER','SCISSOR']
            b= random.randint(1,3)
            if (u=='1' and b==1) or (u=='2' and b==2) or (u=='3' and b==3):
                print(" "*64,"YOUR CHOICE :",a[int(u)-1])
                print(" "*64,"COMPUTER CHOICE :",a[b-1])
                print(" "*64,"DRAW")
                print(" "*64,"BOTH 1 POINT")
                cp+=1
                up+=1
                print(" "*64,"YOUR SCORE :",up)
                print(" "*64,"COMPUTER SCORE :",cp)
            elif (u=='1' and b==2) or (u=='2' and b==3) or (u=='3' and b==1):
                print(" "*64,"YOUR CHOICE :",a[int(u)-1])
                print(" "*64,"COMPUTER CHOICE :",a[b-1])
                print(" "*64,"YOU LOSE")
                cp+=1
                print(" "*64,"YOUR SCORE :",up)
                print(" "*64,"COMPUTER SCORE :",cp)
            elif (u=='3' and b==2) or (u=='1' or b==3) or (u=='2' and b==1):
                print(" "*64,"YOUR CHOICE :",a[int(u)-1])
                print(" "*64,"COMPUTER CHOICE :",a[b-1])
                print(" "*64,"YOU WIN")
                up+=1
                print(" "*64,"YOUR SCORE :",up)
                print(" "*64,"COMPUTER SCORE :",cp)
            else:
                print(" "*64,"Invalid Input")
                break
        elif cp==3:
            print(" ")
            print("_"*109)
            print(" ")
            print(" "*64,"YOU ARE LOOSER ")
            print(" ")
            print("_"*109)
            print(" ")
            break
        elif up==3:
            print(" ")
            print("_"*109)
            print(" ")
            print(" "*64,"YOU ARE WINNER ")
            print(" ")
            print("_"*109)
            print(" ")
            break
        else:
            print(" ")
            print("_"*109)
            print(" ")
            print(" "*64,"DRAW ")
            print(" ")
            print("_"*109)
            print(" ")
            break
def lht():
    up=0
    cp=0
    for i in range (5):
        if up<3 and cp<3 or (cp==up):
            print(" ")
            print("_"*109)
            print(" ")
            print(" "*64,"ROUND",i+1,"".center(130))
            print(" ")
            print("1. LADY".center(130))
            print("2. HUNTER".center(130))
            print("3. TIGER".center(130))
            print(" ")
            u=input("                                                            ENTER YOUR CHOICE :")
            print(" ")
            a=['LADY','HUNTER','TIGER']
            b= random.randint(1,3)
            if (u=='1' and b==1) or (u=='2' and b==2) or (u=='3' and b==3):
                print(" "*64,"YOUR CHOICE :",a[int(u)-1])
                print(" "*64,"COMPUTER CHOICE :",a[b-1])
                print(" "*64,"DRAW")
                print(" "*64,"BOTH 1 POINT")
                cp+=1
                up+=1
                print(" "*64,"YOUR SCORE :",up)
                print(" "*64,"COMPUTER SCORE :",cp)
            elif (u=='1' and b==3) or (u=='2' and b==1) or (u=='3' and b==2):
                print(" "*64,"YOUR CHOICE :",a[int(u)-1])
                print(" "*64,"COMPUTER CHOICE :",a[b-1])
                print(" "*64,"YOU LOSE")
                cp+=1
                print(" "*64,"YOUR SCORE :",up)
                print(" "*64,"COMPUTER SCORE :",cp)
            elif (u=='3' and b==1) or (u=='1' or b==2) or (u=='2' and b==3):
                print(" "*64,"YOUR CHOICE :",a[int(u)-1])
                print(" "*64,"COMPUTER CHOICE :",a[b-1])
                print(" "*64,"YOU WIN")
                up+=1
                print(" "*64,"YOUR SCORE :",up)
                print(" "*64,"COMPUTER SCORE :",cp)
            else:
                print(" "*64,"Invalid Input")
                break
        elif cp==3:
            print(" ")
            print("_"*109)
            print(" ")
            print(" "*64,"YOU ARE LOOSER ")
            print(" ")
            print("_"*109)
            print(" ")
            break
        elif up==3:
            print(" ")
            print("_"*109)
            print(" ")
            print(" "*64,"YOU ARE WINNER ")
            print(" ")
            print("_"*109)
            print(" ")
            break
        else:
            print(" ")
            print("_"*109)
            print(" ")
            print(" "*64,"DRAW ")
            print(" ")
            print("_"*109)
            print(" ")
            break
def Quit():
    print(" ")
    print("_"*109)
    print(" ")
    print("THANK YOU".center(130))
    print("ANY KIND OF ISSUE IS REGRETED, PLEASE CONTACT US ".center(130))
    print(" mananpoddar307@gmail.com".center(135))
    print("_"*109)
    print(" ")
    print("THANK YOU FOR USING THIS APPLICATION ".center(130))
    print(" ")
    print("DEVELOPER - SHIVRAJ & MANAN".center(130))
    print("_"*109)

c = '1'
while(c=='1'):
    print("_"*109)
    print(" ")
    print("APNA GAME".center(130))
    print(" ")
    print(" "*9,"DATE:",t_date.day,"/",t_date.month,"/",t_date.year,"                                                                                       TIME:",t_time.hour ,":",t_time.minute)
    print(" ")
    print("_"*109)
    print(" ")
    print(" "*64,"1.SNAKE WATER GUN")
    print(" "*64,"2.STONE PAPER SCISSOR")
    print(" "*64,"3.LADY HUNTER TIGER")
    print(" "*64,"4.QUIT")
    print(" ")
    print(" ")
    choice=input("                                                            ENTER YOUR CHOICE :")
    print(" ")
    if choice=='1':
        swg()
    elif choice=='2':
        sps()
    elif choice=='3':
        lht()
    else:
        Quit()
        break
