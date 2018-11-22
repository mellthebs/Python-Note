## Numpy

##### Numpy是Python中用于科学计算的核心库。它提供了高性能的多维数组对象，以及相关工具。

- #### 数组Arrays

一个numpy数组是一个由不同数值组成的网格。网格中的数据都是同一种数据类型，可以通过非负整型数的元组来访问。维度的数量被称为数组的阶，数组的大小是一个由整型数构成的元组，可以描述数组不同维度上的大小。

我们可以从列表创建数组，然后利用方括号访问其中的元素：

	import numpy as np
	
	a = np.array([1, 2, 3])  # Create a rank 1 array
	print type(a)            # Prints "<type 'numpy.ndarray'>"
	print a.shape            # Prints "(3,)"
	print a[0], a[1], a[2]   # Prints "1 2 3"
	a[0] = 5                 # Change an element of the array
	print a                  # Prints "[5, 2, 3]"
	
	b = np.array([[1,2,3],[4,5,6]])   # Create a rank 2 array
	print b                           # 显示一下矩阵b
	print b.shape                     # Prints "(2, 3)"
	print b[0, 0], b[0, 1], b[1, 0]   # Prints "1 2 4"
