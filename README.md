# Data-frame_google-colab

Создадим DataFrame с одним столбцом, содержащим категориальные данные и получим список уникальных значений из столбца.

Для каждого уникального значения создадим новый столбец в DataFrame, который будет содержать 1, если значение в исходном столбце совпадает с текущей категорией, и 0 в противном случае.

Столбец 'whoAmI': Это исходные данные, которые мы случайным образом сгенерировали и перемешали.

Столбец 'robot' и 'human': Это новые столбцы, которые были созданы в результате преобразования в формат one-hot. В этих столбцах установлено значение 1, если соответствующая строка в столбце 'whoAmI' соответствует 'robot' или 'human', и 0 в противном случае.




