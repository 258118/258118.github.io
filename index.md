# Welcome To My Website
 CDT501 

## My name

Li Qianyi

## Python script with AI assistance

import numpy as np
import matplotlib.pyplot as plt

x = np.linspace(0, 10, 100)
y1 = np.sin(x)
y2 = np.cos(x)

plt.plot(x, y1, 'r-', label='sin(x)')
plt.plot(x, y2, 'b--', label='cos(x)')
plt.xlabel("时间 (s)")
plt.ylabel("幅度")
plt.title("正弦波与余弦波")
plt.legend()
plt.grid(True)
plt.show()
