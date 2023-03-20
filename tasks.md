
## Задача 1.   
### Создать элемент в HTML и добавить ему стиль с помощью JavaScript.  
1. Создать элемент (div) с помощью JavaScript.    
2. Добавить текст внутри элемента с помощью JavaScript.  
3. Добавить класс к элементу с помощью JavaScript.  
4. Добавить стиль к элементу с помощью JavaScript:   
- background-сolor: blue;  
- color: white;  
- padding: 10px;  
5. Добавить элемент в HTML с помощью JavaScript в начало body.  

## Задача 2.   
### Написать функцию addClass  
Написать функцию addClass, которая будет принимать элемент и класс, и добавлять этот класс к элементу.  
Работать должна так:   
![image](https://user-images.githubusercontent.com/113675674/217232848-268ddfe1-b3dd-48b8-9398-b773b1e157d5.png)   

## Задача 3.   
### с помощью JavaScript  
У вас есть такой HTML:  
`<div class="div1">div 1</div>`  
1. создать элемент div и добавить его перед div class="div1".  
2. задать класс созданному элементу 'div2'  
3. добавить  ему css свойства: background-color: gainsboro; padding: 10px;  
4. клонировать созданный элемент с классом 'div2' и добавить его после div class="div1".  
5. удалить элемент  div class="div1" и на его место вставить новый созданный элемент div class="div3"  
6. div class="div3" добавить css свойства: background-color: red; padding: 10px;  
Должно получиться так:  
![image](https://user-images.githubusercontent.com/113675674/225556040-b7e04168-1855-4058-8981-52c0b4b4804c.png)  


## Задача 4.   
### Изменение текста в инпуте  
Создайте функцицю buttonClick, которая будет менять текст в инпуте на "!!!".  
HTML код:  
`<button onclick="buttonClick()">Нажми на меня</button>`  
`<input type="text" id="input" value="???">`  
JS код:  
`function buttonClick() {  
//ваш код  
}`  
 ![image](https://user-images.githubusercontent.com/113675674/225561079-e2a6d242-2d0b-48c4-9fef-8c595b0d281e.png)  
![image](https://user-images.githubusercontent.com/113675674/225561123-04b95744-766f-419b-a4ec-ad44207ee21f.png)  


## Задача 5.   
### Вывод содержимого инпута  
Создайте функцицю buttonClick2, которая будет выводить алертом содержимое инпута.  
HTML код:  
`<button onclick="buttonClick2()">Нажми на меня</button>`  
`<input type="text" id="input2" value="а вот и я">`  
JS код:  
`function buttonClick2() {  
//ваш код  
}`  
![image](https://user-images.githubusercontent.com/113675674/225560836-575a69f6-a9f1-4671-a064-25d18d0c5ce2.png)    
![image](https://user-images.githubusercontent.com/113675674/225560740-7addaaf9-3981-4da4-b4da-5d2e1dae63e6.png) 


## Задача 6.   
### Квадрат содержимого инпута  
Создайте функцицю buttonClick3, которая будет водить алертом содержимое инпута, возведенное в квадрат.  
HTML код:  
`<button onclick="buttonClick3()">Нажми на меня</button>`  
`<input type="text" id="input3" placeholder="Введите число!">`  
JS код:  
`function buttonClick3() {  
//ваш код  
}` 

![image](https://user-images.githubusercontent.com/113675674/217238781-c94bed60-ce4d-45cd-8230-f48e70ab1852.png)  
![image](https://user-images.githubusercontent.com/113675674/217238824-8df83447-be9c-4a37-a2dc-9608251bc108.png)  

## Задача 7.   
### Работа с CSS  
Создайте функцицю buttonClick4, которая будет менять цвет текста внутри инпута на красный.  
HTML код:  
`<button onclick="buttonClick4()">Нажми на меня</button>`  
`<input type="text" id="input4" value="Какой-то текст!">`  
JS код:  
`function buttonClick4() {  
//ваш код  
}` 

![image](https://user-images.githubusercontent.com/113675674/217240004-79495ddd-dbd9-4187-b54a-eaeea1e75763.png)  
![image](https://user-images.githubusercontent.com/113675674/217240033-2972b831-773e-4592-8323-637221f56995.png)  

### Задача 7/1. дополнительная  
Создайте функцицю buttonClick4, которая будет менять цвет текста внутри инпута рандомно, т.е. при повторном нажатии должен быть изменен цвет на другой.  
Воспользуйтесь массивом цветов: `let colors = ['chocolate', 'red', 'blue', 'green', 'yellow', 'blueviolet', 'aqua', 'cornflowerblue', 'darkslateblue', 'coral', 'darkgoldenrod'];`   
Нужно генерировать случайное число с помощью `Math.random()`, но помните, он возвращает от 0 до 1 (не включая 1), так что умножте его на 10 =)  
А еще придется округлить до целого числа.  
И таким образом вы будете рандомно выбирать индекс у массива цветов.  
HTML код:  
`<button onclick="buttonClick4()">Нажми на меня</button>`  
`<input type="text" id="input4" value="Какой-то текст!">`  
JS код:  
`function buttonClick4() {  
//ваш код  
}` 
 

## Задача 8.   
### Блокирование полей ввода  
У вас две кнопки, одна из них блокирует инпут с помощью атрибута disabled, а другая разблокирует.  Напишите функции button1Click и button2Click для этих кнопок.  
Прочитайте про [disabled](https://code.mu/ru/markup/manual/html/attr/disabled/)  
`<button onclick="button1Click()">Заблокировать</button>`  
`<button onclick="button2Click()">Отблокировать</button>`  
`<input type="text" id="input5" value="Какой-то текст!">`  

![image](https://user-images.githubusercontent.com/113675674/217243374-36da6fe9-8aee-4b32-b05e-0b663382b124.png)  
![image](https://user-images.githubusercontent.com/113675674/217243415-1682bc25-6a1e-4b60-8de0-d6a2403aa79a.png)  

## Задача 9.   
### Меняем цвет фона   
Есть две кнопки и массив `let colorsBack = ['chocolate', 'red', 'blue', 'green', 'yellow', 'blueviolet', 'aqua', 'cornflowerblue', 'darkslateblue', 'coral', 'darkgoldenrod'];`  
При нажатии на первую кнопку меняется бэкграунд у `body`,  рандомно выбирается цвет из массива `colorsBack` .   
При нажатии на вторую кнопку бэкграйнд у `body` становится первоначальным.  
HTML код:  
    `<button id="changeColorButton" onclick="changeBackgroundColor()">Change Color</button>`  
    `<button id="resetColorButton" onclick="resetBackgroundColor()">Reset Color</button>`  
JS код:  
`function changeBackgroundColor() {  
//ваш код  
}`  
`function resetBackgroundColor() {  
//ваш код  
}`  

