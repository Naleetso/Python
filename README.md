<h2>| Задание 44 |</h2>

<h3>В ячейке ниже представлен код генерирующий DataFrame, которая состоит всего из 1 столбца. Ваша задача перевести его в one hot вид. Сможете ли вы это сделать без get_dummies?</h3>

import random<br>
lst = ['robot'] * 10<br>
lst += ['human'] * 10<br>
random.shuffle(lst)<br>
data = pd.DataFrame({'whoAmI'lst})<br>
data.head() |
