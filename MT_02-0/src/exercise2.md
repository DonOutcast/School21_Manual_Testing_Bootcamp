# Список тестовых сценариев

## Авторизация в приложении

**Сценарий №1_1. Проверка успешного прохождения авторизации (LOGIN):**
1. Перейти на страницу авторизации
2. В поле "Username" ввести "standard_user"
3. В поле "Password" ввести "secret_sauce"
4. Нажать на кнопку "LOGIN"

**Сценарий №1_2. Проверка успешного прохождения авторизации (ENTER):**
1. Перейти на страницу авторизации
2. В поле "Username" ввести "standard_user"
3. В поле "Password" ввести "secret_sauce"
4. Нажать на клавишу "ENTER"

**Сценарий №1_3. Проверка возможности разлогиниться**
1. Перейти на страницу авторизации
2. В поле "Username" ввести "standard_user"
3. В поле "Password" ввести "secret_sauce"
4. Нажать на кнопку "LOGIN"
5. На основной странице (all items) нажать на иконку с тремя черточками (слева вверху)
6. В выезжающем списке нажать на кнопку "LOGOUT"

## Сортировка товаров

### Сортировка товаров на странице всех товаров

**Сценарий №2_1. Сортировка товаров в обратном алфавитном порядке**
1. Перейти на страницу авторизации
2. В поле "Username" ввести "standard_user"
3. В поле "Password" ввести "secret_sauce"
4. Нажать на кнопку "LOGIN"
5. На основной странице (all items) нажать на кнопку "NAME (A-Z)" (справа вверху)
6. В выпадающем списке выбрать вариант сортировки "Name Z to A"

**Сценарий №2_1. Сортировка товаров в алфавитном порядке**
1. Перейти на страницу авторизации
2. В поле "Username" ввести "standard_user"
3. В поле "Password" ввести "secret_sauce"
4. Нажать на кнопку "LOGIN"
5. На основной странице (all items) нажать на кнопку "NAME (A-Z)" (справа вверху)
6. В выпадающем списке выбрать вариант сортировки "Name A to Z"

**Сценарий №2_3. Сортировка товаров в порядке возрастания цены**
1. Перейти на страницу авторизации
2. В поле "Username" ввести "standard_user"
3. В поле "Password" ввести "secret_sauce"
4. Нажать на кнопку "LOGIN"
5. На основной странице (all items) нажать на кнопку "NAME (A-Z)" (справа вверху)
6. В выпадающем списке выбрать вариант сортировки "Price (low to high)"

**Сценарий №2_4. Сортировка товаров в порядке убывания цены**
1. Перейти на страницу авторизации
2. В поле "Username" ввести "standard_user"
3. В поле "Password" ввести "secret_sauce"
4. Нажать на кнопку "LOGIN"
5. На основной странице (all items) нажать на кнопку "NAME (A-Z)" (справа вверху)
6. В выпадающем списке выбрать вариант сортировки "Price (high to low)"

## Работа с корзиной

**Сценарий №3_1. Добавление одной единицы товара в корзину**
1. Перейти на страницу авторизации
2. В поле "Username" ввести "standard_user"
3. В поле "Password" ввести "secret_sauce"
4. Нажать на кнопку "LOGIN"
5. На основной странице (all items) выбрать одну единицу товара и нажать на кнопку "ADD TO CART"
6. Перейти в корзину - нажать кнопку корзины справа вверху

**Сценарий №3_2. Добавление нескольких единиц товара в корзину**
1. Перейти на страницу авторизации
2. В поле "Username" ввести "standard_user"
3. В поле "Password" ввести "secret_sauce"
4. Нажать на кнопку "LOGIN"
5. На основной странице (all items) выбрать несколько единиц товара и нажать на кнопку "ADD TO CART" под каждым товаром
6. Перейти в корзину - нажать кнопку корзины справа вверху

**Сценарий №3_3. Удаление товара из корзины**
1. Перейти на страницу авторизации
2. В поле "Username" ввести "standard_user"
3. В поле "Password" ввести "secret_sauce"
4. Нажать на кнопку "LOGIN"
5. На основной странице (all items) выбрать одну единицу товара и нажать на кнопку "ADD TO CART"
6. Перейти в корзину - нажать кнопку корзины справа вверху
7. Нажать на кнопку "REMOVE" в карточке товара

## Оформление заказа

**Сценарий №4_1. Оформление заказа с одной единицей товара**
1. Перейти на страницу авторизации
2. В поле "Username" ввести "standard_user"
3. В поле "Password" ввести "secret_sauce"
4. Нажать на кнопку "LOGIN"
5. На основной странице (all items) выбрать одну единицу товара и нажать на кнопку "ADD TO CART"
6. Перейти в корзину - нажать кнопку корзины справа вверху
7. Нажать на кнопку "CHECKOUT"
8. В поле "FIRST NAME" ввести имя
9. В поле "SECOND NAME" ввести фамилию
10. В поле "zip/postal code" ввести zip/postal code
11. Нажать на кнопку "CONTINUE"
12. Нажать на кнопку "FINISH"

**Сценарий №4_2. Оформление заказа с несколькими единицами товара**
1. Перейти на страницу авторизации
2. В поле "Username" ввести "standard_user"
3. В поле "Password" ввести "secret_sauce"
4. Нажать на кнопку "LOGIN"
5. На основной странице (all items) выбрать несколько единиц товара и нажать на кнопку "ADD TO CART" под каждым товаром
6. Перейти в корзину - нажать кнопку корзины справа вверху
7. Нажать на кнопку "CHECKOUT"
8. В поле "FIRST NAME" ввести имя
9. В поле "SECOND NAME" ввести фамилию
10. В поле "zip/postal code" ввести zip/postal code
11. Нажать на кнопку "CONTINUE"
12. Нажать на кнопку "FINISH"

## Проверка работы боковой панели

**Сценарий №5_1. Успешное открытие и закрытие боковой панели с основной страницы**
1. Перейти на страницу авторизации
2. В поле "Username" ввести "standard_user"
3. В поле "Password" ввести "secret_sauce"
4. Нажать на кнопку "LOGIN"
5. На основной странице (all items) открыть боковую панель кликом на иконку с тремя полосками в верхнем левом углу
6. Закрыть боковую панель кликом на "крестик"

**Сценарий №5_2. Успешное открытие и закрытие боковой панели со страницы корзины**
1. Перейти на страницу авторизации
2. В поле "Username" ввести "standard_user"
3. В поле "Password" ввести "secret_sauce"
4. Нажать на кнопку "LOGIN"
5. Перейти в корзину - нажать кнопку корзины справа вверху
6. Открыть боковую панель кликом на иконку с тремя полосками в верхнем левом углу
7. Закрыть боковую панель кликом на "крестик"

## Проверка ссылок на странице

**Сценарий №6_1. Проверка возможности перейти в Twitter по кнопке в футере**
1. Перейти на страницу авторизации
2. В поле "Username" ввести "standard_user"
3. В поле "Password" ввести "secret_sauce"
4. Нажать на кнопку "LOGIN"
5. В футере страницы нажать на "птичку" - кнопку перехода на страницу Twitter

**Сценарий №6_2. Проверка возможности перейти в Facebook по кнопке в футере**
1. Перейти на страницу авторизации
2. В поле "Username" ввести "standard_user"
3. В поле "Password" ввести "secret_sauce"
4. Нажать на кнопку "LOGIN"
5. В футере страницы нажать на "букву f" - кнопку перехода на страницу Facebook

**Сценарий №6_3. Проверка возможности перейти в LinkedIn по кнопке в футере**
1. Перейти на страницу авторизации
2. В поле "Username" ввести "standard_user"
3. В поле "Password" ввести "secret_sauce"
4. Нажать на кнопку "LOGIN"
5. В футере страницы нажать на "буквы in" - кнопку перехода на страницу LinkedIn
