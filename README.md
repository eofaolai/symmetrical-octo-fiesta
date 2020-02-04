# symmetrical-octo-fiesta

import matplotlib.pyplot as mp
import numpy as np

x = np.arange(0,2*np.pi,.1)
y = np.sin(x)
z = np.cos(x)
mp.plot(x,y,x,z)
mp.legend(['sin(x)', 'cos(x)'])
mp.show()
