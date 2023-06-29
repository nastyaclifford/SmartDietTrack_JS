# SmartDietTrack
Eat smart - it’s easy and tasty! :)

SmartDietTrack представляет собой учебный проект, веб-сайт для получения информации об основных питательных веществах продуктов, подсчета дневной нормы калорий, а также поиска полезных сбалансированных рецептов. 
Задачей проекта было создание функционального, интерактивного сайта с обязательным применением HTML, SASS, JavaScript, API. 
Веб сайт используется исключительно в целях обучения и не используется в корпоративных целях.

/ ссылка на сайт /

Проектная команда
Екатерина Сафиуллова (https://github.com/Safiullova)
Анжелика (https://github.com/AnzhelikaMullova) 
Анастасия Клиффорд (https://github.com/nastyaclifford)
Mарина Овчаренко (https://github.com/Mmaryna68)
Екатерина Григас (https://github.com/grigaskate)

Описание веб-сайта

Веб-сайт был создан в рамках практической проектной работы в школе IT Girls. Дизайн сайта был разработан командой на основе макета  из фигмы. 
Макет веб-сайта https://www.figma.com/file/FBaI8hSPn5Exv6TCKNzXxh/Healthy-Eating-Template?type=design&node-id=1-430&mode=design&t=YPWvXlBIFaEtEXLM-0

Основа для макета - дизайн в свободном доступе https://www.figma.com/file/NzUxmldLBgTid1UN0AiwJF/Agriculture-Webflow-Website-Template-(Community)?type=design&node-id=2-9967&mode=design&t=26za1y9YxPiBUaVe-0)

Сайт состоит из одной страницы, а также содержит модальное окно. 

Структура сайта
1.Header со ссылками на разделы сайта и именем пользователя. При создании бургер-меню был использован JS. 
2.Баннер, на котором присутствует кнопка с переходом на модальное окно с основной информацией о сайте. Реализация с помощью JS. 
3.Форма для входа. Использовался JS для реализации выведения имени пользователя в header. 
4.Форма для получения информации о питательных веществах продуктов. При создании формы были использованы JS и бесплатная версия API https://www.edamam.com/. При введении продукта в поле появляются подсказки, для этого также был использован API  Edamam.
5.Блок с отзывами пользователей сайта. Отзывы отображаются в виде слайдера, который был реализован с помощью JS.
6.Форма для подсчета дневной нормы потребляемых калорий. При создании формы были использованы JS и бесплатная версия API https://fitness-calculator.p.rapidapi.com. Пользователь должен ввести свои параметры (вес, рост, пол, цель похудения/набора/ поддержания веса), и калькулятор производит рассчет дневной нормы калорий.
7.Форма для вывода рецептов по запросу пользователя. При создании формы были использованы JS и бесплатная версия API https://www.edamam.com/. Пользователь имеет возможность выбрать прием пищи (завтрак, обед, ужин и тд), а также ввести ингредиент, который будет использоваться в приготовлении блюда. Рецепты выводятся в рандомном порядке.
8.Форма для подписки на новости и обновления. При создании формы были использованы JS и бесплатный API с цитатами https://type.fit/api/quotes. После отправки данных, пользователю выводится сообщение с благодарностью и цитатой-мотивацией.
9.Footer со ссылками на разделы сайта. 

При создании сайта использовались следующие технологии и инструменты
JavaScript
HTML5
SASS, CSS
GitHub
APIs (https://fitness-calculator.p.rapidapi.com, https://www.edamam.com/,   https://type.fit/api/quotes)



Инструкция по установке 


GitHub ссылка на проект https://github.com/3Girls-team/SmartDietTrack/tree/MASTER
1)Для того, чтобы перенести проект себе на компьтер, необходимо выполнить команду git clone и вставить код https://github.com/3Girls-team/SmartDietTrack.git  в терминале VS Code
2)Html код страницы находится в файле index.html
3)Js код находится в файле index.js

4) Js код для слайдера с отзывами находится в папке itc-slider.js
3) Путь к файлам Sass: SmartDietTrack/assets/styles/scss/components/
стили для header страницы (_header.scss)
стили для блока Баннер (_banner.scss)
стили для модального окна (_modal.scss)
стили для формы регистрации (_registrationForm.scss)
стили для блока с выводом питательных веществ о продуктах (_nutrients.scss)
стили для блока отзывы (_itc-slider.scss, _testimonial.scss)
стили для блока калькулятор калорий (_calculator.scss)
стили для блока с выводом рецептов (_randomRecipe.scss)
стили для блока с формой подписки (_formNews.scss)
cтили для footer (_footer.scss)
4)Текстовые стили находятся в папке SmartDietTrack/assets/styles/scss/_fonts.scss

5)Стили для кнопок и полей ввода находятся в папке SmartDietTrack/assets/styles/scss/_mixins.scss

6)Стили для разных цветов находятся в папке SmartDietTrack/assets/styles/scss/_vars.scss

7)Все файлы со стилями собираются и импортируются в файле SmartDietTrack/assets/styles/scss/index.scss

8)Используемые изображения находятся в файле SmartDietTrack/assets/images
