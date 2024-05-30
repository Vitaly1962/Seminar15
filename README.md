# Seminar15 | В ячейке ниже представлен код генерирующий DataFrame, которая состоит всего из 1 столбца. 
Задача состоит в том чтобы перевести его в one hot вид. Можно ли это сделать без get_dummies?

import random
lst = ['robot'] * 10
lst += ['human'] * 10
random.shuffle(lst)
data = pd.DataFrame({'whoAmI'lst})
data.head()
