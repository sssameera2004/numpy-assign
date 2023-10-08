1. Create a null vector of size 10 but the fifth value which is 1.

import numpy as np

# create null vector of size 10
null_vector = np.zeros(10)

# set the fifth value to 1
null_vector[4] = 1

print(null_vector)

2.Create a vector with values ranging from 10 to 49
Z=np.arange(10,50)
print (Z)
[10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30 31 32 33 34
 35 36 37 38 39 40 41 42 43 44 45 46 47 48 49]

3. Create a 3x3 matrix with values ranging from 0 to 8

Z = np.arange(9).reshape(3,3)
print (Z)
[[0 1 2]
 [3 4 5]
 [6 7 8]]


4.Find indices of non-zero elements from [1,2,0,0,4,0]

nz = np.nonzero([1,2,0,0,4,0])
print(nz)
(array([0, 1, 4]),)



5.Create a 10x10 array with random values and find the minimum and maximum values
Z = np.random.random((10,10))
Zmin, Zmax = Z.min(), Z.max()
print(Zmin, Zmax)
0.0113751594253 0.995035059799


6.Create a random vector of size 30 and find the mean value

Z = np.random.random(10)
m = Z.mean()
print (m)
