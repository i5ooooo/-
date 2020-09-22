# -d={"1":"周嘉诚","3":"钱龙超","4":"徐展","5":"尤按哲","6":"钱涛","7":"黄舒怡","8":"胡志辉",}
import random
n=3
a = random.sample(d.keys(), n)
for i in a:
   print(d[i])
