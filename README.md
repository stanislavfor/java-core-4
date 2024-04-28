# Java Core (семинары)
## Урок 4. Обработка исключений
### ДЗ тут:
1.
Создать программу управления банковским счетом (Account).<br>
Программа должна позволять пользователю вводить начальный баланс счета, сумму депозита и сумму снятия средств.<br><br> При этом она должна обрабатывать следующие исключительные ситуации:

- Попытка создать счет с отрицательным начальным балансом должна вызывать исключение IllegalArgumentException с соответствующим сообщением.<br>
- Попытка внести депозит с отрицательной суммой должна вызывать исключение IllegalArgumentException с соответствующим сообщением.<br>
- Попытка снять средства, сумма которых превышает текущий баланс, должна вызывать исключение InsufficientFundsException с сообщением о недостаточных средствах и текущим балансом.

**Продемонстрируйте работу вашего приложения:**<br>
Программа должна обрабатывать все исключения с помощью конструкции try-catch, выводя соответствующие сообщения об ошибках.

### Дополнительное, не обязательное задание:
2.
Создать несколько типов счетов, унаследованных от Account, например: CreditAcciunt, DebitAccount.<br><br>
Создать класс (Transaction), позволяющий проводить транзакции между счетами (переводить сумму с одного счета на другой)

Класс Transaction должен возбуждать исключение в случае неудачной попытки перевести деньги с одного счета на другой.

**Продемонстрируйте работу вашего приложения:**<br>
Программа должна обрабатывать все исключения с помощью конструкции try-catch, выводя соответствующие сообщения об ошибках.

*Достаточно выпонить только первую задачу, вторая задача является дополнительной.*