# АЛГОРИТМЫ И ЛОГИКА

1. факториал в цикле
1. рекурсивный факториал def f(n); n.zero? ? 1 : n * f(n-1); end
1. фибонначи в цикле
1. рекурсивный фибоначчи def b(n); (n <= 1) ? 1 : b(n-1) + b(n-2); end
1. напишите алгоритм, определяющий, есть ли в массиве 2 элемента дающие в сумме n, оценить сложность. Массив отсортирован (можно за O(n)). Пример: n = 8; wrong = [2,5,7,11]; correct = [1,2,4,4] # true
1. 7 монет, 1 фальшивая весит легче, за сколько взвешиваний можно найти фальшивую на весах-чашах?
1. 7 монет, 1 фальшивая отличается по весу неизвестно в какую сторону, за сколько взвешиваний можно найти фальшивую на весах-чашах?
1. На прямой 2 робота, случайно ориентированы. Могут ехать вперёд-назад или стоять на месте. Составить алгоритм, который позволяет гарантированно им столкнуться
1. Есть замкнутый в кольцо поезд, без окон, вагоны разделены дверями, вы внутри. В каждом вагоне есть лампочка, лампочки находятся в случайном состоянии. Как посчитать количество вагонов
1. Найти все варианты расстановки 8 ферзей на шахматной доске (8*8) так, чтобы они не били друг друга. Написать программу для нахождения расстановок для произвольного N (N ферзей, доска N*N). Учитывать симметричные варианты
1. Между двумя столбами высотой 50 метров натянут провод длиной 80 метров. Нижняя его точка не достаёт до земли на 10 метров. Найти на каком расстоянии находятся столбы
1. В теннисном турнире сто двадцать семь участников. В первом туре сто двадцать шесть игроков составят шестьдесят три пары, победители которых выйдут в следующий тур, и еще один игрок выходит во второй тур без игры. В следующем туре — шестьдесят четыре игрока сыграют тридцать два матча. Сколько всего матчей понадобится, чтобы определить победителя?
1. Поменять 2 числа местами не используя параллельное присваивание и третью переменную
1. Определить, является ли слово анаграммой другого. Для произвольного словаря найти все анаграммы.
1. Определить, является ли строка строкой из сбалансированных скобок
1. В клетки квадрата `N*N` записать числа по спирали
1. В клетки квадрата `N*N` записать числа по двойной спирали
1. Проверить, является ли многоугольник выпуклым. Дан набор его вершин в виде массива Декартовых координат
1. Полтора принтера за полторы минуты печатают полтора журнала. Сколько журналов напечатают 9 принтеров за 9 минут?


# ШИФРЫ

1. Каждая буква в тексте заменена на букву алфавита с определённым сдвигом. Расшифровать текст.
1. Каждая буква в тексте зашифрована XOR
1. Текст зашифрован с использованием таблицы замены.
  Каждая буква заменена на некоторую другую произвольную букву того же алфавита.
  Попытаться его расшифровать

1. Оптимальная нарезка древесины. Дан набор досок разной длины и набор деталей для распиловки.
  Определить, можно ли вырезать необходимые детали из имеющегося набора
  Найти оптимальный способ, при котором остаётся меньше всего отходов.
  Отходами считаем деталь, из которой более нельзя сделать ни одной детали

1. Решить систему линейных алгебраических уравнений