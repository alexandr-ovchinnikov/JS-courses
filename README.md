# JS-courses
<<<<<<< HEAD
1. Ознакомиться с GIT
2. Ознакомиться с GitHub
3. Форкнуть репозиторий
4. Добавить index.html
5. Создать пулл реквест

##  GIT
[Основы GIT](https://git-scm.com/book/ru/v1/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%9E-%D0%BA%D0%BE%D0%BD%D1%82%D1%80%D0%BE%D0%BB%D0%B5-%D0%B2%D0%B5%D1%80%D1%81%D0%B8%D0%B9)

[Github help](https://help.github.com/)

[Видеокурс](https://www.youtube.com/watch?v=PEKN8NtBDQ0)

##  JS
[Основы JS](https://learn.javascript.ru/first-steps)


## JS задачи
1. реализовать функцию которая вернет сумму элементов произвольного массива
2. реализовать функцию которая принимает произвольный массив и возвращает отсортированный по возростанию, сделать двумя способами, через метод sort и через цикл for
3. реализовать функцию которая возвращает массив с уникальными элементами // [1,1,2,3,1,2] => [1,2,3]
4. реализовать функцию которая возвращает массив с числами фибоначчи, количество которых зависит от переданного значения при вызове функции
=======
1. Прочитать статьи
3. При выполнении заданний надо использовать деструктуризацию где это можно
2. Сделать пулл реквест с выполненными заданиями

##  JS
[Методы для перебора массивов](https://learn.javascript.ru/array-iteration)

Пересмотреть [Методы массива](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Array)

[Деструктуризация](https://learn.javascript.ru/destructuring)


## JS задачи
1. Реализовать функцию которая возвращает массив его частичных сумм // [1,2,3,4,5] => [1, 3, 6, 10, 15]
2. Реализовать функцию которая вернет новый массив на основе этого https://pastebin.com/0xvghaeT, элементы которого должны быть объектами и иметь поля id, name и avaragePrice - среднее арифметическое от суммы firstPrice и secondPrice.
3. Реализовать функцию которая вернет массив с элементами в которых avaragePrice > 5000, элементы массива должны быть отсортированны по полю avaragePrice, по возростанию. Массив брать из вызова функции задания 2.
4. Деструктурировать свойства из [JSON](https://pastebin.com/tTqELBxC): 
    * requestId, 
    * result.accountNumber, 
    * result.balance.otb, 
    * result.cards.ucid, 
    * result.cards.expireDate
    * result.cards.expireDate.year,
    * result.overdraftInfo.lastCloseDayOverBalance, 
    * result.bank.id
    
   Пример: 
   ```
   const {requestId} = {...};
   const {requestId123} = {...};
   ```
PS. Обязательное условие - пишем на новом стандарте. var => let/const, () => {} вместо function - когда актуально и т.д. Кто еще не ознакомился - [ES6](https://learn.javascript.ru/es-modern)
>>>>>>> 4a425205bf29e7ac23eccfb92064c3b397ace171
