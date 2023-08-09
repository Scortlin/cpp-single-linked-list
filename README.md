# cpp-single-linked-list
Финальный проект: односвязный список.
Single-linked List – это модель линейного однонаправленного списка.

Односвязный список допускает следующие операции:

1) вставка элемента в начало или конец списка;
2) вставка элемента после некоторого элемента списка;
3) удаление элемента, следующего за данным элементом спискa;
4) проверка списка на пустоту;
5) определение количества элементов в списке;

# Функционал

1) Операции сравнения списков между собой. Поддерживаются операторы равенства и неравенства: сравнение происходит лексикографически.
2) Обмен содержимого двух списков, соответствующий идиоме copy-and-swap.
3)Конструирование односвязного списка на основе std::initializer_list. Последовательность элементов сохраняется.
4) Конструктор копирования и операция копирующего присваивания. Обеспечена строгая гарантия безопасности исключений. Если в процессе присваивания будет выброшено исключение – объект присваивания сохранится в прежнем состоянии.
5) Метод PushFront вставляет узел в начало списка. Предоставляет строгую гарантию безопасности исключений.
6) Метод PopFront. Удаляет первый узел непустого списка. Имеет константную временную сложность O(1). Не выбрасывает исключений.
7) Метод Clear очищает список и не выбрасывает исключений.
8) Метод InsertAfter. За время O(1) вставляет в список новый узел после указанного элемента. Метод обеспечивает строгую гарантию безопасности исключений.
9) Метод EraseAfter. За время O(1) удаляет из списка узел после указанного элемента. Не выбрасывает исключений.
10) Методы before_begin и cbefore_begin. Возвращают итераторы, ссылающиеся на фиктивную позицию перед первым элементом списка.
