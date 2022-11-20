# ITGirlsHomeworkW14

1. Какие есть способы объявления функций?
   function declaration (в основном потоке кода)
   function expression (как чать выражения)
   arrow function (без слова function, =>)

2. Приведите примеры вызова одной и той же функции всеми известными вам способами.
   имя*функции ()
   имя*переменной ()

3. В чем разница между тестированием и отладкой (дебаггингом)? А что такое логирование?
   тестирование - проверка работы кода, может выполпяться вручную и с помощью специальных программ.
   отладка позволяет выполнить поиск и исправить ошибки в коде пошагово при его выполнении с помощью командды debugger.

4. В чем разница между Function Expression и Function Declaration?
   Разница в способе объявления и в моменте создания функции, когда JS начинает выполнять её. При function declaration функция может использоваться во всем скрипте. function expression создаётся, когда до неё доходит выполнение кода.

5. Что делает функция console.log()?
   Позволяет вывести и проверить значения и сообщения в консоли.

6. Что такое BOM и DOM?
   BOM - объектная модель браузера, часть JavaScript, которая позволяет скрипту взаимодействовать с программой просмотра веб-страниц. Представляет объекты, через свойства и методы которых можно управлять внешним видом и поведением обозревателя.
   DOM - объектная модель документа. Представляет собой структуру документа в виде узлов и объектов, которые доступны с помощью JS.

7. Как найти

1) Таблицу с id="age-table"
   document.getElementById('age-table');
2) Все элементы label внутри этой таблицы (их три)
   document.getElementsByTagName('label');
3) Форму form с именем name="search-person"
   document.getElementsByName('search-person')

8. Как сделать переход на другую страницу при клике на кнопку только средствами JavaScript)?
   можно использовать код window.location.href = 'адрес*другой*страницы';

9. Как можно обнулить (очистить) значение внутри input?
   document.getElementById('id инпута').value = "";

10. Как будет выглядеть ваша функция приветствия из прошлого домашнего задания, если ее переписать в стрелочном формате?
    let personName = () => {
    let person = prompt("Your name")
    alert(`Hello, ${person}!`)
    }

personName()
