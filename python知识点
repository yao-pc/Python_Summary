集合用add
ports.add(i)
ports.remove(a)
str.insert(cursor, c)
str.pop(cursor - 1)
"".join(l_str)
tmp = cmd.split(' ')
res = [i.replace(" ", "") for i in ids]
res = [i for i in r_list if re.match(r'^[A-Za-z][\d]+$', i)]
res = [i for i in r_list if len(i) < 5]
res = [i[0].lower() + i[1].zfill(8) for i in r_list]
res = sorted(set(res))
if set(num).issuperset(set(str(i))):
min([max(np.array(matrix)[:, x]) for x in range()])

num = list(map(int, re_num))

字典排序
d = {'b': 2, 'a': 1, 'c': 3}
# 按键排序，返回排序后的 (key, value) 元组列表
sorted_items = sorted(d.items())
print(sorted_items)  # [('a', 1), ('b', 2), ('c', 3)]
# 如果你想构建一个新字典（保持排序顺序）
sorted_dict_by_key = dict(sorted(d.items()))
print(sorted_dict_by_key)  # {'a': 1, 'b': 2, 'c': 3}

d = {'b': 2, 'a': 1, 'c': 3}
# 按值排序（升序）
sorted_by_value = dict(sorted(d.items(), key=lambda item: item[1](data:{"action":"setReference","index":"1"})))
print(sorted_by_value)  # {'a': 1, 'b': 2, 'c': 3}
# 按值排序（降序）
sorted_by_value_desc = dict(sorted(d.items(), key=lambda item: item[1](data:{"action":"setReference","index":"1"}), reverse=True))
print(sorted_by_value_desc)  # {'c': 3, 'b': 2, 'a': 1}
• 




• isdigit()
• isalpha()
• isdecimal()  # 类似于 isdigit()，但更加严格地限制为十进制数字（不包括上标、罗马数字等）  
• isspace()
• islower()
• isupper()
• istitle()
• 
`split()` 和 `re.split()` 处理分隔符的机制完全不同**。
简单来说：`split()` 是“切掉”分隔符，而 `re.split()` 的捕获组是“把分隔符也切出来”。
在正则表达式模块 `re` 中，`re.split()` 的行为取决于**分隔符是否被括号 `()` 捕获（Capture Group）**。
* **非捕获分组**：如果正则表达式只是 `r'[*/+-]'`，行为就和 `split()` 一样，分隔符会被丢弃。
* **捕获分组**：如果你加了括号 `r'([*/+-])'`，正则引擎会执行一个特殊的逻辑：**“不仅把字符串切开，还要把被括号捕获的那一部分（也就是分隔符本身）也作为结果的一部分返回”**。


• 
np_matrix = np.array(matrix)
np_matrix.min()  #'list' object has no attribute 'min'，转换为array才可以

• update() 是字典的一个内置方法，用于将传入的字典中的键值对添加到当前字典中。如果键已经存在，则更新对应的值；如果键不存在，则添加新的键值对。


tt_list=re.split(r'([*/+-])',expression)


matrix.max(axis=0)
axis=0：对每一列，从上往下找最大值
axis=1：对每一行，从左往右找最大值

i.zfill(8)
i 必须是字符串类型，否则会报错。
正确做法是先转成字符串：
str(123).zfill(8)  # → "00000123"
zfill(8) 只补 '0'，不会处理负数符号（如 -123）。
"-123".zfill(8)  # → "-0000123"
f"{int(i):08d}"  # 等价于 i.zfill(8)，但更灵活

import numpy as np
max(np.array(matrix)[:, x]) for x in range(m)  # 矩阵也有切片

无穷大形式
写法	含义
float('inf')	正无穷大（+∞）
float('-inf')	负无穷大（-∞）
float('nan')	非数字（Not a Number），用于表示无效数值

来自 <https://xiaoluban.huawei.com/> 



defaultdict(list) 
defaultdict(list) 是 Python 中 collections 模块的一个类，它继承自字典（dict）并提供了自动初始化默认值的功能。
使用 defaultdict(list) 时，当你访问一个不存在的键时，它会自动创建一个空的 list 作为该键的值，而无需手动检查键是否存在。
示例：
from collections import defaultdict
# 创建一个 defaultdict，其默认值是空列表
dd = defaultdict(list)
# 添加元素到不同的键
dd['fruits'].append('apple')
dd['fruits'].append('banana')
dd['vegetables'].append('carrot')
print(dd)
输出：
defaultdict(<class 'list'>, {'fruits': ['apple', 'banana'], 'vegetables': ['carrot']})


集合用.add()，列表用.append()
ports.add(i)
ports.remove(a)
str.insert(cursor, c)
str.pop(cursor - 1)
del dic(i)
"".join(l_str)
tmp = cmd.split(' ')
res = [i.replace(" ", "") for i in ids]
res = [i for i in r_list if re.match(r'^[A-Za-z][\d]+$', i)]  # r 是 Python原始字符串前缀
ans = [f"port trunk allow-pass vlan {vlan_ids[0]}"]  # f 是 Python 的 f-string（格式化字符串字面量）前缀
re.findall('\d{4,}', value)
res = [i for i in r_list if len(i) < 5]
res = [i[0].lower() + i[1].zfill(8) for i in r_list]
res = sorted(set(res))
if set(num).issuperset(set(str(i))):
min([max(np.array(matrix)[:, x]) for x in range()])  # 矩阵也有切片
滑窗while right < len(str):
str1 not in str2:
for i in range(1, len(steps)):  step(i-1), step(i)
素数：从3开始遍历奇数相乘
DFS：深度优先搜索->调用栈本身特性
BFS：广度优先搜索->邻接表+队列先进先出
import sys -> sys.maxsize
初始化中的入参肯定是要用到的，可以单独初始化，亦可放到其他数据中
字典排序：tmp = sorted(self.device_type_dict[device_type].items(), key=lambda x: (-x[1]["remain"], x[0]))
字典的键可以为整型

import math
from collections import deque

a |= b   # 并集

bisect
bisect.bisect_left(a, x) 在有序列表 a 中查找插入位置 x，使得 x 插入后仍保持有序，且如果 x 已存在，插入到最左侧。
bisect.bisect_right(a, x)/bisect.bisect(a, x)  在有序列表 a 中查找插入位置 x，使得 x 插入后仍保持有序，且如果 x 已存在，插入到最右侧。
sa.insert(bisect.bisect(sa, res_temp), res_temp)

math.ceil()
math.sqrt()

获取字母的 ASCII 码  ord('A')  chr(65)

区间合并
涉及多个区间且有重合的，可以初始化总长度然后遍历赋值
def calcute(self, data: List):  #[开始，结束，步数]
	data.sort()
	res_sum = 0
	lst = [0, 0]
        # 整理数据
        res = [0] * (data[-1][1]+1)
        for i in data:
		 for j in range(i[0], i[1]):
			res[j] = max(res[j], i[2])
	if len(res) <= 120:
		return  [data[0][0], sum(res)]
	for m in range(len(res)-120):
		if res_sum < sum(res[m: m+120]):
			res_sum = sum(res[m: m+120])
			lst = [m, res_sum]
	return lst

字典赋值
for i in records:
	if i[0] not in dic.keys():
		dic[i[0]] = [i[1:]]
	else:
		dic[i[0]].append(i[1:])

字典排序
res = sorted(dic.items(), key=lambda x:(-x[1][1], x[0]))  # [(1, [2, 3]), (4, [5, 6])]

temp_traits = traits 是引用赋值，不是复制
这会导致原始 traits 列表被修改
在后续循环中 temp_traits[0] 可能不存在
用temp_traits = traits.copy() 


 # 末尾增加一个元素0，不用对数组越界情况做特殊处理
vlan_ids.append(0)
