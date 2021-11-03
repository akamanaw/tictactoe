# tictactoe
How to code that someone wins and tie

from tkinter import *

AusgabeO = True;
button_nr1 = True;
button_nr2 = True;
button_nr3 = True;
button_nr4 = True;
button_nr5 = True;
button_nr6 = True;
button_nr7 = True;
button_nr8 = True;
button_nr9 = True;


def button_action1():
    global AusgabeO
    global button_nr1
    if button_nr1==True:
        button_nr1=False
        if AusgabeO:
            nr1_button.config(text="o")
            AusgabeO=False
        else:
            nr1_button.config(text="x")
            AusgabeO = True
    
def button_action2():
    global AusgabeO
    global button_nr2
    if button_nr2==True:
        button_nr2=False
        if AusgabeO:
            nr2_button.config(text="o")
            AusgabeO=False
        else:
            nr2_button.config(text="x")
            AusgabeO=True
        
def button_action3():
    global AusgabeO
    global button_nr3
    if button_nr3==True:
        button_nr3=False
        if AusgabeO:
            nr3_button.config(text="o")
            AusgabeO=False
        else:
            nr3_button.config(text="x")
            AusgabeO=True

def button_action4():
    global AusgabeO
    global button_nr4
    if button_nr4==True:
        button_nr4=False
        if AusgabeO:
            nr4_button.config(text="o")
            AusgabeO=False
        else:
            nr4_button.config(text="x")
            AusgabeO=True
        
def button_action5():
    global AusgabeO
    global button_nr5
    if button_nr5==True:
        button_nr5=False
        if AusgabeO:
             nr5_button.config(text="o")
             AusgabeO=False
        else:
             nr5_button.config(text="x")
             AusgabeO=True
        
def button_action6():
    global AusgabeO
    global button_nr6
    if button_nr6==True:
        button_nr6=False
        if AusgabeO:
             nr6_button.config(text="o")
             AusgabeO=False
        else:
             nr6_button.config(text="x")
             AusgabeO=True
        
def button_action7():
    global AusgabeO
    global button_nr7
    if button_nr7==True:
        button_nr7=False
        if AusgabeO:
             nr7_button.config(text="o")
             AusgabeO=False
        else:
             nr7_button.config(text="x")
             AusgabeO=True
        
def button_action8():
    global AusgabeO
    global button_nr8
    if button_nr8==True:
        button_nr8=False
        if AusgabeO:
             nr8_button.config(text="o")
             AusgabeO=False
        else:
             nr8_button.config(text="x")
             AusgabeO=True
        
def button_action9():
    global AusgabeO
    global button_nr9
    if button_nr9==True:
        button_nr9=False
        if AusgabeO:
             nr9_button.config(text="o")
             AusgabeO=False
        else:
             nr9_button.config(text="x")
             AusgabeO=True

fenster = Tk()
fenster.title("TIC-TAC-TOE")
fenster.geometry("450x400")

nr1_button = Button(fenster, command=button_action1)
nr1_button.place(x = 100, y = 20, width= 50, height=90)

nr2_button = Button(fenster, command=button_action2)
nr2_button.place(x = 200, y = 20, width= 50, height=90)

nr3_button = Button(fenster, command=button_action3)
nr3_button.place(x = 300, y = 20, width= 50, height=90)

nr4_button = Button(fenster, command=button_action4)
nr4_button.place(x = 100, y = 120, width= 50, height=90)

nr5_button = Button(fenster, command=button_action5)
nr5_button.place(x = 200, y = 120, width= 50, height=90)

nr6_button = Button(fenster, command=button_action6)
nr6_button.place(x = 300, y = 120, width= 50, height=90)

nr7_button = Button(fenster, command=button_action7)
nr7_button.place(x = 100, y = 220, width= 50, height=90)

nr8_button = Button(fenster, command=button_action8)
nr8_button.place(x = 200, y = 220, width= 50, height=90)

nr9_button = Button(fenster, command=button_action9)
nr9_button.place(x = 300, y = 220, width= 50, height=90)











fenster.mainloop()
