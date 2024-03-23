# Порівняння алгоритмів сортування

## Результати експерименту (час виконання в секундах, для послідовностей з 5000 елементів, 10 ітерацій):

- **Insertion Sort**:
  - Випадкові дані: 6.530
  - Частково відсортовані дані: 7.914
  - Дані, відсортовані в зворотному порядку: 0.468

- **Merge Sort**:
  - Випадкові дані: 0.926
  - Частково відсортовані дані: 0.538
  - Дані, відсортовані в зворотному порядку: 0.506

- **Timsort**:
  - Випадкові дані: 0.112
  - Частково відсортовані дані: 0.114
  - Дані, відсортовані в зворотному порядку: 0.099

## Висновок

Timsort демонструє вищу продуктивність у різних типах наборів даних, підкреслюючи його придатність як універсального алгоритму сортування, особливо для наборів даних, що можуть містити частково відсортовані послідовності, завдяки своїм оптимізаціям для реальних сценаріїв. Merge Sort залишається міцним вибором завдяки своїй передбачуваній продуктивності O(n*log n) та стабільності, тоді як Insertion Sort може бути переважним для маленьких наборів даних або наборів даних, які майже відсортовані, через його простоту та низькі накладні витрати.