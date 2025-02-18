# university-algo-fp

## Завдання 7
# Висновки

Під час порівняння результатів методу Монте-Карло і аналітичних розрахунків для ймовірностей сум після кидання двох кубиків ми можемо зробити наступні спостереження:

1. **Порівняння результатів:**
   
   | Сума | Ймовірність (Monte Carlo) | Ймовірність (Вхідні дані)|
   |------|---------------------------|--------------------------|
   | 2    | 0.0279                    | 0.0278                   |
   | 3    | 0.0552                    | 0.0556                   |
   | 4    | 0.0837                    | 0.0833                   |
   | 5    | 0.1110                    | 0.1111                   |
   | 6    | 0.1396                    | 0.1389                   |
   | 7    | 0.1664                    | 0.1667                   |
   | 8    | 0.1383                    | 0.1389                   |
   | 9    | 0.1107                    | 0.1111                   |
   | 10   | 0.0835                    | 0.0833                   |
   | 11   | 0.0556                    | 0.0556                   |
   | 12   | 0.0279                    | 0.0278                   |

2. **Порівняння точності:**

   Загальною тенденцією є те, що результати методу Монте-Карло досить близькі до аналітичних розрахунків, але в деяких випадках може спостерігатися невелике відхилення. Ми отримали майже ідентичні дані.

3. **Точність обчислень:**

   Зазвичай, точність обчислень методом Монте-Карло залежить від кількості випробувань. Збільшення кількості випробувань може покращити точність результатів.

4. **Ресурси та час:**

   Метод Монте-Карло є більш універсальним підходом, оскільки він може використовувати значно менше ресурсів для складних проблем, але в той же час він може вимагати більше часу для досягнення точних результатів.
   