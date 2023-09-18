# cpp-single-linked-list

Implemented an analogue of the template class Single-linked list (forward_list) from the standard library. Data is stored in nodes created in dynamic memory (in the heap). Each node stores a value and a pointer to the next node in the list.

A custom forward_iterator type iterator is implemented for the list. Comparison operators, dereference operator * and access operator -> are implemented for iterators. The increment operator ++ is implemented.

Реализован аналог шаблонного класса Односвязный список (forward_list) из стандартной библиотеки. Данные хранятся в нодах, создаваемых в динамической памяти (в куче). Каждая нода хранит значение и указатель на следующую ноду в списке.

Для списка реализован собственный итератор типа forward_iterator. Для итераторов реализованы операторы сравнения, оператор разыменования * и доступа ->. Реализован оператор инкремента ++.
