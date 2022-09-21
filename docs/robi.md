# Robert Arryn

```python
import numpy as np
import matplotlib.pyplot as plt
from matplotlib import animation

fig = plt.figure()
ax = plt.subplot()
plt.plot(0, 0)

t = np.linspace(-2*np.pi, 2*np.pi, 500)
a = 1
b = 5
d = np.pi/2

x = np.sin(a * t + d)
y = np.sin(b * t)

plt.plot(x, y)
plt.show()

```

![bg](/_media/bg2.jpg)

