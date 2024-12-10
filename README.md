
# Веб-сайт — Interno «Лучшие интерьерные решения»
+ Проект реализован на Vue.js
+ Без адаптива на планшеты и смартфоны

+ Макет:
https://www.figma.com/design/BgRBjvHgBrfaEliss8CDOS/Макет-для-итоговой-аттестации-на-Frontend-разработчике?node-id=1-5&node-type=canvas

+ Презентация с использованием серчиса Vercel:
https://interno-blond.vercel.app/

## Компоненты
+ Весь проект поделён на компоненты, можно работать с пропсами и выводить компоненты удобным способом, чтобы можно было их сортировать или менять.
+ Компоненты шапки и подвала позволяют переключаться между страницами.

## Blog
+ Добавлен блок «Статьи & Новости», где данные для вёрстки хранится в массиве объектов и выводятся на страницу с помощью цикла v-for.
+ На странице отображается подробное описание одной статьи, а под ней размещаются остальные.

## Blog Details
+ Отображается подробное описание статьи.
+ При выборе «Тега» происходит сортировка статей по выбранному тегу. Тег можно выбрать только один.

## Project
+ В блоке categories сделано переключение проектов.
+ Выполнена пагинация.
 
## ProductDetails
+ Компонент отображает детали о конкретном продукте, включая название, цену и статус доступности.
+ Доработано изменение контента по категориям и по тегам.
+ Сделан слайдер.

## NotFound
+ Добавлена страница 404, которая появляется, если пользователь переходит по несуществующей ссылке.

## VueX
Управление данными приложения с VueX:
+ Реализована работа со state.
+ Взаимодействие между компонентами через VueX.
+ Информация про описание проекта вынесена в state.

## Vue-Router
Навигация в приложении Vue-Router:
+ Добавлено переключение страниц через Vue-Router.

## CSS
+ Добавлены переменные шрифтов.
+ Добавлено управление переносами.
+ Добавлены переменные ’place-content’ и ’place-item’ там, где это возможно.
