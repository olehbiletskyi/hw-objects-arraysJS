# hw-objects-arraysJS
>
1. Створити обєкт який описує тварину (назву, вагу, вік, середню швидкість), і наступні функції для роботи з ним:
>
Функція яка виведе всю інформацію про тварину. 
Функція яка виведе за скільки тварина зможе подолати 1000 км. (врахуйте що тварина може рухатись не більше 12 годин у день). 
Функція яка зможе змінити назву тварини на більш детальну.
>
2. Створіть обєкт який має у собі 2 довжини сторін фігури. 
>
Додайте методи які будуть робити наступне:
рахувати площу фігури, 
периметр фігури, 
зроблять фігуру 3-д, 
зададуть назву фігури, 
переведуть значення з сантиметрів у метри.
>
3. Створимо аналог списка покупок (мінімум 5 покупок з всіма заданими пропертями.)
>
let products = {
                tomato: {
                    count: 5,
                    price: 50,
                    buy: false,
                    inStore: true
                },
  ...
}
>
Виводимо список покупок - спочатку ті, які є в магазині, потім яких нема.
Виводимо список покупок, які ми купили.
Додаємо функцію, яка дозволить купити продукт.
Додаємо функцію, яка просумує всі зроблені покупки і виведе результат (не забуваємо, що є значення кількості та ціни за одиницю товару).
Додаємо можливість збільшувати кількість товару.
Додаємо можливість зменшувати кількість товару(менше 0 бути не може).
>
4. Задана колекція [{name: "Yura", age: 55, hobby: ["films", "games", "hiking"], type: "Admin"}, {}, {},{}].
>
Вивести всіх адмінів. 
Вивести середній вік усіх працівників. 
Вивести тільки унікальні хоббі працівників.