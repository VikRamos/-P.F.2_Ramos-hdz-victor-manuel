# -P.F.2_Ramos-hdz-victor-manuel
ventana
from tkinter import *                    #llamamos las librerias
from tkinter.ttk import *
![image](https://user-images.githubusercontent.com/79875910/112209709-5da51580-8bdf-11eb-853d-974527d42e34.png)


window = Tk()
window.title("programa")                                              #con windos tk inicializamos o arrancamos un programa
lbl = Label(window, text="robot",font =("Arial Bold",50))             #tenemos un objeto etiqueta con sus atributos de palabras
lbl.grid(column=0,row=0)                                              #pocicionamiento de etiqueta
![image](https://user-images.githubusercontent.com/79875910/112209783-79a8b700-8bdf-11eb-938b-bdbd71a4ebaa.png)


txt=Entry(window,width=0)                                             #tenemos otros objetos de texto con su pocicionamiento 
txt.grid(column=0,row=1)
txt.focus()                                                           #objeto focus
![image](https://user-images.githubusercontent.com/79875910/112210037-cc826e80-8bdf-11eb-98c6-385aa5d49105.png)




def Cliked():
    res = "inteligencia artificial" + txt.get()                         #metodo clik asignamos este evento y las secuencias que tendra al pulsar este objeto esque manda a llamar
    lbl.configure(text=res)                                             
 ![image](https://user-images.githubusercontent.com/79875910/112210187-03f11b00-8be0-11eb-9598-691cfbd6e240.png)

indow.geometry("500x500")
btn = Button(window, text="clik",command=Cliked)
btn.grid(column=1,row=1)
window.mainloop()
![image](https://user-images.githubusercontent.com/79875910/112210357-3569e680-8be0-11eb-82cd-17545adbc6de.png)
