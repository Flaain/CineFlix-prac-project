# ![Image alt](https://github.com/flaain/CineFlix-prac-project/raw/master/images/logo/logo.png) тренировочный проект
____
## Описание проекта
 ```
Проект из себя представляет бесплатный онлайн-кинотеатр
```

 ```
 В основе проекта лежит методология БЭМ, поэтому все элементы независимы 
 друг от друга и могут использоваться на странице повторно
```
____
### Главная страница проекта
![Image alt](https://github.com/flaain/CineFlix-prac-project/raw/master/images/Screenshot_1.png)
### Блок с карточками фильмов
![Image alt](https://github.com/flaain/CineFlix-prac-project/raw/master/images/Screenshot_2.png)
____
### Блок с карточками выполнен с использованием технологии построения сетки

 ```css
.cards__list {
    display: grid;
    grid-template-columns: repeat(auto-fill, 176px);
    row-gap: 30px;
    justify-content: space-between;
    margin: 0;
    padding: 0;
    list-style: none;
}
```
### Демонстрация анимации карточек
![Image alt](https://github.com/flaain/CineFlix-prac-project/raw/master/images/cards-animation.gif)
