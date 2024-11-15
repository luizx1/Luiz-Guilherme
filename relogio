from tkinter import Label, Tk
import time

clock_window = Tk()
clock_window.title("Relógio")
clock_window.geometry('400x150')
clock_window.resizable (1,1)
text_style = ("Boulder", 65, 'bold')
content = Label(clock_window, font=text_style,
                bg= "#1b1f22", fg ="#9461fb", bd=25)
content.grid (row=0, column=1)
def clock():
    hours = time.strftime("%H:%M:%S")
    content.config(text=hours)
    content.after(200, clock)
clock()
clock_window.mainloop()
