```python

import math

print("digite o angulo que você deseja")
L=float(input(""))
print()
Sen=math.sin(math.radians(L))
print(f"o angulo de {L} tem o seno de {Sen:.2f}")
Cos=math.cos(math.radians(L))
print()
print(f"o angulo de {L} tem o coseno de {Cos:.2f}")
print()
Tan=math.tan(math.radians(L))
print(f"o angulo de {L} tem a tangente de {Tan:.2f}")
print()
