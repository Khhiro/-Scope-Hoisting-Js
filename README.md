# Что такое `Scope` и `Hoisting` на Js 

![alt text](https://www.cronj.com/blog/wp-content/uploads/Artboard-33.png)

## Что такое `Scope`

--> `Scope` это (Область видимость) или место нохождения. 

Scope-имя'Область видимости (или scope) в JS – это как "зона доступа" 🚧 для переменных и функций. Если переменная объявлена глобально 🌍, её видно везде. Локально 🏠 – только внутри функции.

![](https://itchief.ru/assets/images/covers/javascript-scope-and-context.png)

```js
// Глобальная область

function foo1(){
    // Локальная область 1
  function foo2(){
    // Локальная область 2
  }
}

// Глобальная область
function foo3(){
  // Локальная область 3
}

// Глобальная область
```

## Что такое `Hoisting` на `Js`

Hoisting – это уникальная особенность JavaScript, которая позволяет вам обращаться к переменным и функциям до того, как они были объявлены в коде.

![](https://sky.pro/wiki/og-images/javascript/hoisting-v-javascript-chto-eto-var-let-const-i-funkcii.png)


```js
function catName(name) {
  console.log("Мою кошку зовут " + name);
}

catName("Тигр");
/*
Результатом будет вывод строки: "Мою кошку зовут Тигр"
*/

```

![](https://i.ytimg.com/vi/E4OUfMZX76U/maxresdefault.jpg)
