# 21
12
import pickle

with open('data.pickle', 'rb') as f:  # 以二进制读取的方式打开文件
  data = pickle.load(f)  # 加载数据

print(data)  # 输出加载的数据
