# 10219077
Dwita Gurning


## materi sebelumnya
+ Materi-materi sebelumnya yang telah diberikan antara lain adalah : 
1. Persamaan Lorentz
2. Predator-Prey Equation
3. Euler's Method
4. Runge Kutta 4th Order Methods
5. Monte Carlo Methods
6. DFT
7. FFT
8. Sistem Rantai Membentang


## materi paling menarik
+ Tuliskan materi yang paling menarik yang telah diberikan dan jelaskan mengapa menarik.
Materi yang paling menarik adalah Metode Monte Carlo. Metode ini menarik karena terkait dengan tugas akhir saya dan berhubungan dengan bermain tebak-tebakan.


## materi paling membosankan
+ Tuliskan materi yang telah diberikan yang paling membosankan dan jelaskan alasannya.
Materi yang paling membosankan adalah Runge Kutta Orde 4. Alasannya adalah karena belum mengerti bagaimana mengaplikasikannya kedalam persoalan sistem fisisnya.


## materi yang sudah dipami
+ Tuliskan materi-materi yang telah dipahami.
Materi yang telah dipahami :
1. Euler's Method
2. Monte Carlo Methods
3. Sistem Rantai Membentang



## materi yang belum dipahami
+ Tuliskan materi-materi yang masih belum dipahami dan bagian mana yang belum serta ingin dipahami.
Materi yang masih belum dipahami dan yang ingin dipahami.
1. Persamaan Lorentz
2. Predator-Prey Equation
3. Runge Kutta 4th Order Methods
4. Monte Carlo Methods
5. DFT
6. FFT

## contoh program
+ Buat suatu contoh program dalam Python dan sertakan di sini dengan hasil keluarnnya.

```python
# contoh program python
# estimasi nilai pi

import matplotlib.pyplot as plt
import random

inside = 0
n = 100

xinside = []
yinside = []
xoutside = []
youtside = []

for _ in range (n):
    x = random.uniform(-1,1)
    y = random.uniform(-1,1)
    if x**2+y**2 <=1:
        inside+=1
        xinside.append(x)
        yinside.append(y)
        
    else:
        xoutside.append(x)
        youtside.append(y)
        
```

Hasilnya adalah

```
pi = 4*inside/n
print('nilai estimasi pi', pi)

fig, ax = plt.subplots()
ax.set_aspect('equal')
ax.scatter(xinside, yinside, color='g', marker  ='s')
ax.scatter(xoutside, youtside, color ='r', marker = 's')

plt.draw()

```

## cara perkuliahan
+ Tuliskan pendapat Anda mengenai cara perkuliahan selama ini dan cantumkan usulan untuk perkuliahan setelah UTS.


## topik sistem fisis
+ Tuliskan sistem fisis yang menarik bagi Anda untuk dikaji lebih dalam dan jelaskan alasannya mengapa.


## simulasi dan visualisasi
+ Apakah Anda tertarik dengan simulasi dan visualisasi? Jelaskan topik yang ingin Anda simulasikan / visualisasikan serta cantumkan alasannya dan perkiraan pusataka Python yang perlu digunakan.
