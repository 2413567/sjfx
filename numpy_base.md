# numpy 

## np基础

16/05/2023 10:22

* * *

### 基础数组

```
import numpy as np
 
ary = np.arry([1,2,3])
```

- 数组的维度
    `ary.shape`
    输出为元组 ,行列
    `ary.shape = (2,3)`乘积要够
    
- 数组的运算
    

```
import numpy as np
 
ary = np.arry([1,2,3])
print（ary*3）
[3,6,9]
```

- numpy内所有元素为统一数据类型
* * *
## ndarry创建
- np.arange(0, 5, 1) （起始值，终止值， 步长）
- np.zeros(元素个数(可以是维度数组)， dtype=数据类型)
- np.ones(元素个数(可以是维度数组)， dtype=数据类型)
- 扩展
np.ones_like(a) 
np.zeros_like(a)
创建维度像a的全0或全1的ndarry数组
* * *
### 数组的属性
- 维度
ndarry.shape
- 数据类型
np.ndarry.dtype
转换类型使用astype（）
- 元素个数
np.ndarry.size
- 数组索引取值
1. ndarry[0][1][2]
2. ndarry[0, 1, 2]

