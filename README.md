# Try-using-np.sort-and-np.where-with-3D-array-using-NumPy
import numpy as np  arr = np.array([[[1, 2], [3, 4]], [[5, 6], [7, 8]]])  for x in np.nditer(arr):   print(x)   x = np.where(arr == 4)  print(x)  print (np.sort(arr))
