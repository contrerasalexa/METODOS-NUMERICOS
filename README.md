# METODOS-NUMERICOS
Materia metodos numericos, codigos de python
import Numpy as np

def f(x):
    return x - 0.8-0.2*np.sin(x)

a= 0
b= np.pi

c = a - (f(a)(b-a)/f(b)-f(a))
