# Labka-1-neyron-sety
Цель лабораторной работы: ознакомление с основами языка Python и библиотекой NumPy для научных вычислений.
import numpy as np

a_array = np.arange(10)
print("Берілген массив:", a_array)
print("3 пен 6 элементтер арасындағы сандар:", a_array[3:7])
a_array[7:10] = [10, 20, 30]

print("Өзгертілген массив:", a_array)
