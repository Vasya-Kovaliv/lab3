s-блок
Цей код реалізує пряме і зворотне перетворення за алгоритмом S-блоку.
Спочатку визначена таблиця констант Constants, яка використовується для прямого перетворення. Ця таблиця містить 4 підтаблиці розміром 4x4, де кожне значення відповідає вхідним та вихідним даним. Функція compute_inverse_constants обчислює таблицю констант для зворотного перетворення. Функція s_block_forward здійснює пряме перетворення за алгоритмом S-блоку. Функція s_block_inverse здійснює зворотне перетворення за алгоритмом S-блоку.
p-блок
У цьому прикладі використано таблицю перестановок P для прямого і зворотного перетворення p_box реалізує пряме перетворення, а функція reverse_p_box реалізує зворотне перетворення, формула перестановки задається в змінній p_permutation.
