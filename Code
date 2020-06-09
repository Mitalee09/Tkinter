from tkinter import *

root = Tk()
root.title("Calculator")
e = Entry(root, width = 40, borderwidth = 8)
e.grid(row = 0, column = 0, columnspan = 3, padx = 10, pady = 10)

def button_click(number):
    #e.delete(0, END)
    current = e.get()
    e.delete(0, END)
    e.insert(0, str(current) + str(number))

def button_clear():
    e.delete(0, END)

def button_add():
    first_number = e.get()
    global f_num
    global math
    math = "addition"
    f_num = int(first_number)
    e.delete(0, END)

def button_equal():
    second_number = e.get()
    e.delete(0, END)
    if math == "addition":
        e.insert(0, f_num + int(second_number))

    if math == "subtraction":
        e.insert(0, f_num - int(second_number))

    if math == "multiplication":
        e.insert(0, f_num * int(second_number))

    if math == "division":
        e.insert(0, f_num / int(second_number))

    if math == "power2":
        e.insert(0, f_num ** int(2))

    if math == "power":
        e.insert(0, f_num ** int(second_number))

    if math == "power3":
        e.insert(0, f_num ** int(3))

def button_subtract():
    first_number = e.get()
    global f_num
    global math
    math = "subtraction"
    f_num = int(first_number)
    e.delete(0, END)

def button_multiply():
    first_number = e.get()
    global f_num
    global math
    math = "multiplication"
    f_num = int(first_number)
    e.delete(0, END)

def button_divide():
    first_number = e.get()
    global f_num
    global math
    math = "division"
    f_num = int(first_number)
    e.delete(0, END)

def button_power2():
    first_number = e.get()
    global f_num
    global math
    math = "power2"
    f_num = int(first_number)
    e.delete(0, END)

def button_power():
    first_number = e.get()
    global f_num
    global math
    math = "power"
    f_num = int(first_number)
    e.delete(0, END)

def button_power3():
    first_number = e.get()
    global f_num
    global math
    math = "power3"
    f_num = int(first_number)
    e.delete(0, END)


#Define buttons

button1 = Button(root,text = "1", padx = 40, pady = 20, command = lambda: button_click(1),bg = "black",fg = "white")
button2 = Button(root,text = "2", padx = 40, pady = 20, command = lambda: button_click(2), bg = "black",fg = "white")
button3 = Button(root,text = "3", padx = 40, pady = 20, command = lambda: button_click(3), bg = "black",fg = "white")
button4 = Button(root,text = "4", padx = 40, pady = 20, command = lambda: button_click(4), bg = "black",fg = "white")
button5 = Button(root,text = "5", padx = 40, pady = 20, command = lambda: button_click(5), bg = "black",fg = "white")
button6 = Button(root,text = "6", padx = 40, pady = 20, command = lambda: button_click(6), bg = "black",fg = "white")
button7 = Button(root,text = "7", padx = 40, pady = 20, command = lambda: button_click(7), bg = "black",fg = "white")
button8 = Button(root,text = "8", padx = 40, pady = 20, command = lambda: button_click(8),bg = "black",fg = "white")
button9 = Button(root,text = "9", padx = 40, pady = 20, command = lambda: button_click(9), bg = "black",fg = "white")
button0 = Button(root,text = "0", padx = 40, pady = 20, command = lambda: button_click(0), bg = "black",fg = "white")
button_add = Button(root,text = "+", padx = 39, pady = 20, command = button_add, bg = "red", fg = "white")
button_equal = Button(root,text = "=", padx = 89, pady = 20, command = button_equal, bg = "yellow", fg = "black")
button_clear = Button(root,text = "Clear", padx = 80, pady = 20, command = button_clear)

button_subtract = Button(root,text = "-", padx = 41, pady = 20, command = button_subtract, bg = "green", fg = "white")
button_multiply = Button(root,text = "x", padx = 40, pady = 20, command = button_multiply,bg = "green", fg = "white")
button_divide = Button(root,text = "/", padx = 41, pady = 20, command = button_divide,bg = "green", fg = "white")
button_power = Button(root,text = "X*", padx = 38, pady = 20, command = button_power, bg = "pink", fg = "black")
button_power2 = Button(root,text = "x2", padx = 37, pady = 20, command = button_power2, bg = "pink", fg = "black")
button_power3 = Button(root,text = "x3", padx = 38, pady = 20, command = button_power3, bg = "pink", fg = "black")

#Put the buttons on the screen

button1.grid(row =3 , column =0)
button2.grid(row =3 , column =1)
button3.grid(row =3 , column =2)

button4.grid(row =2 , column =0)
button5.grid(row =2 , column =1)
button6.grid(row =2 , column =2)

button7.grid(row =1 , column =0)
button8.grid(row =1 , column =1)
button9.grid(row =1 , column =2)

button0.grid(row =4 , column =0)
button_add.grid(row = 5 ,column = 0)
button_equal.grid(row = 5  ,column = 1, columnspan = 2)
button_clear.grid(row = 4 ,column = 1, columnspan = 2)

button_subtract.grid(row = 6, column = 0)
button_multiply.grid(row = 6, column = 1)
button_divide.grid(row = 6, column = 2)
button_power.grid(row = 7, column = 0)
button_power2.grid(row = 7, column = 1)
button_power3.grid(row = 7, column = 2)

root.mainloop()
