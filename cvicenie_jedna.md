---
layout: page
title: "Cvičenie 1."
permalink: /cvicenie_jedna/
---

# Cvičenie 1


```python
#kniznica na kreslenie grafov
import matplotlib.pyplot as plt
#numericko matematicka kniznica
import numpy as np
```


```python
#konštanty
alpha=1/137
htrans_c=200 #Mev fm
```

$b = \frac{\alpha ~z~ \hbar~ c}{E_{\alpha}} ~ \cot(\vartheta/2) $


```python
def b(E_alpha,theta,Z):
    b=alpha*Z*htrans_c/(E_alpha*np.tan(theta/2))
    return b
```


```python
b(20,1/180*np.pi,79)
```




    660.76666862886555

