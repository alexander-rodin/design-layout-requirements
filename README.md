# Требования к макетам дизайна

**Как делать дизайн, который полюбят верстальщики**

> “Первый макет я нарисовал вообще без сетки, прямоугольником, и потом долго уверял верстальщика, что он кретин”

![Grid](https://raw.githubusercontent.com/Rodin-A/Design-layout-requirements/master/img/1.png)

_Данные требования ни в коем случае не несут цели подавить фантазию дизайнера, а предлагают некоторые рамки, работа в которых позволит сделать верстку максимально быстрой и качественной. И положительно скажутся на дальнейшей разработке и развитии проекта. Всегда есть место компромиссу, всегда можно чуть-чуть подвинуться, стерпеть отход от общей сетки в отдельном блоке. Но все компромиссы должны быть оправданы, а не являться следствием лени или некомпетентности._

_После завершения своей работы дизайнеру важно контролировать качество реализации задумки, можно сказать, вести авторский надзор. Только в таком случае реализованный проект будет предметом гордости для всех членом команды._

## Содержание

1. [Общее](#Общее)
2. [Модульность](#Модульность)
3. [Сетка](#Сетка)
4. [Типовые элементы UI](#Типовые-элементы-UI)
5. [Изображения и иконки](#Изображения-и-иконки)
6. [Размеры](#Размеры)
7. [Слои](#Слои)
8. [Текст](#Текст)
9. [Адаптивный дизайн](#Адаптивный-дизайн)
10. [В задаче про это не напишут](#В-задаче-про-это-не-напишут)
11. [Статьи и видео по теме](#Статьи-и-видео-по-теме)

## <a name="Общее"></a>Общие требования

1. Необходимо стремиться к тому, чтобы верстальщик ни в чём не нуждался и не просил.
2. Все спорные места, которые могут вызывать вопросы у разработчика — должны быть описаны или продемонстрированы.
3. Макеты должны быть подготовлены таким образом, чтобы исключить из них всё лишнее, будь то ненужные слои из прошлого, либо оставшаяся графика за пределами артбордов.
4. Для удобства работы с макетом рекомендуется придерживаться кириллических названий слоёв или хотя бы групп.
5. Дизайнер должен учитывать мелочи и постоянно задавать себе вопрос — А что если?… Например: А что, если в моём красивом блоке может отсутствовать какой-либо элемент?

## <a name="Модульность"></a>Модульность

1. Дизайнерам следует создавать не сайты, а модули, которыми наполняется сайт. Необходимо стремиться к мышлению, что каждый большой проект — это конструктор из маленьких деталей. Для создания стилей этих блоков создаются и утверждаются главная и типовая страницы.
2. Необходимо всегда придерживаться уже созданных сущностей, блоков, модулей и не плодить то же самое, только в чуть ином стиле.
3. Допускается максимум 3 варианта страниц, в каждом из которых определены конфигурации контентных областей, которые могут произвольно заполняться модулями.

## <a name="Сетка"></a>Сетка

1. Модульная сетка — это база, по которой строится интерфейс. Это необходимость в любом большом проекте.
2. Отказываться от стандартной сетки можно только в исключительных случаях, если это медиа или промо-проекты.
3. Стандарт модульной сетки — 12 колонок с делениями на 2, 3, 4 или 6 колонок.
4. Сетку можно встраивать внутрь сетки другой сетки. При этом, вложенная сетка имеет столько же колонок.
5. Дизайнер самостоятельно устанавливает размеры сетки, колонок и отступов между ними. В дальнейшем, во всех макетах этого проекта следует использовать только данные размеры.
6. Разрешается использовать различные размеры сетки, колонок и отступов при разработке макетов под различные экраны (Компьютер, Планшет, Телефон).
7. В каждом макете, дизайнеру рекомендуется создавать отдельный слой с полупрозрачным отображением колонок и отступов между ними.
8. Сетка нужна не просто так. Основные элементы, блоки, текст должны быть выровнены по границам колонок.

## <a name="Типовые-элементы-UI"></a>Типовые элементы UI

1. После утверждения главной и типовой страницы, дизайнер создаёт отдельные макеты с набором всех основных элементов проекта
2. Макет с набором основных элементов и их состояний должен содержать:

   1. Заголовки 6-и уровней (H1, H2, H3…)
   2. Стандартный параграф
   3. Стандартная ссылка

      1. :link — ссылка, еще не посещенная пользователем;
      2. :hover — ссылка, на которую наведен курсор;
      3. :active — активная ссылка (та, по которой совершается клик, или на которой удерживается кнопка мыши);
      4. :visited — посещенная ссылка.

   4. Стандартный жирный текст
   5. Стандартный курсивный текст
   6. Нумерованный список
   7. Маркированный список
   8. Параграф с изображением
   9. Пример изображения
   10. Пример изображения с подписью
   11. Цитата
   12. Таблица

3. Макет с набором всех цветов проекта. Все цвета следует назвать и разбить на группы ([образец](https://design.alfabank.ru/style/colors))
4. Все элементы форм и их состояниями (normal, active, hover, disabled, outline, error). Стандартный набор состоит из:
   1. Стандартная форма ввода (input)
   2. Форма ввода текста (textarea)
   3. Отмеченный элемент (checkbox)
   4. Выбранный элемент (radiobutton)
   5. Выпадающий список (select)
   6. Кнопки (Button)
5. Другие интерактивные элементы (баннеры, нестандартные кнопки, карточка новости и др – normal, active, hover, disabled, outline)

## <a name="Изображения-и-иконки"></a>Изображения и иконки

1. Всё, что может быть векторным — должно быть векторным.
2. Растровые изображения необходимо предоставлять в двух размерах (по умолчанию и х2).
3. Логотипы рекомендуется предоставлять отдельным файлом (svg, в крайнем случае – png).
4. Все иконки проекта должны быть векторными, не содержать сложных эффектов (тени, свечение) и без проблем экспортироваться в svg.
5. Все однотипные иконки должны быть вписаны в одинаковый контейнер (например, 24х24, 48х48, 64х64 px).
6. В макете запрещаются все иконки-ссылки (смарт-объекты на Adobe Illustrator и тому подобные). Если это векторная графика — значит в макете это должны быть объекты path, shape.
7. Для набора иконок рекомендуется придерживаться контейнера одного размера, внутри которого векторная графика может располагаться как угодно.
8. Для интерфейсных иконок настоятельно рекомендуются наборы одного производителя (например, [material.io](https://material.io/tools/icons/))
9. Авторские иконки следует рисовать самостоятельно. Нельзя использовать готовые иконки с flaticon или freepic.
10. Все растровые изображения, содержащие несколько слоёв, эффекты, подписи, должны быть слиты в одно изображение. Исключение составляют наложения, обозначающие эффекты при наведении, различные состоянии изображения.
11. При использовании фоновых изображений на всю ширину экрана — следует придерживаться размеров от 1920 пикселей по горизонтальной стороне.

## <a name="Размеры"></a>Размеры

1. Дизайнеру следует придерживаться размеров, кратных 8-ми. ([подробнее](https://habr.com/company/everydaytools/blog/319700/))
2. Текстовый блок должен иметь размер по тексту, исходя из заданных свойств (размер, межстрочный интервал), и не выходить за его пределы.
3. Запрещаются размеры элементов, состоящие из дробных десятичных значений (например: W x H = 960,32px x 640,5px).
4. При создании адаптивных макетов, необходимо помнить, что комфортная область для нажатия пальцем начинается от 44 пикселей

## <a name="Слои"></a>Слои

1. Рекомендуется упорядочивание групп внутри макета в соответствии с расположением на экране (сверху—вниз).
2. Слой не должен иметь режим наложения отличный от режима по умолчанию (Normal Blend mode).
3. Контурные градиенты крайне не рекомендуются.
4. Тени и градиенты легко воспроизводятся в браузере, такие эффекты растрировать не рекомендуется.
5. Все скрытые слои и группы также должны иметь понятное название. Если эти слои и группы не нужны в макете — их следует удалить.
6. От макета к макету — следует придерживаться одних правил и названий. Например, если это шапка сайта, то во всех макетах группа должна называться «Шапка» или «Header». Тоже самое касается упорядочивания для групп слоёв.
7. Если есть скрытые слои или папки, которые показывают какие-то части сайта (модальные окна, выпадающие панели и т.д.) — необходимо выделять папку / слой — цветом, чтобы его не пропустить, также он должен иметь название, которое близко по смыслу его функциональности.

## <a name="Текст"></a>Текст

1. Запрещается трансформирование и модификация размеров шрифта иным способом, кроме стандартного масштабирования.
2. Размер шрифта должен иметь целое число.
3. Все семейства шрифтов должны быть бесплатными, либо иметь лицензию на использование в сети интернет (webfont).
4. Шрифты предоставляются отдельными файлами после утверждения главной и типовой страницы проекта в формате TTF, OTF.
5. Каждый текстовый блок в макете должен находиться на отдельном слое.
6. Запрещено устанавливать отступы между блоками посредством переноса строки.
7. Внутри текстовых блоков также не должно быть переносов текста на другую строку. Переносы зависят только от ширины текстового блока.
8. Каждый текстовый блок должен иметь свой стиль, либо схожий (например, простой текст и курсив). Запрещается использование в одном блоке разных стилей (например, заголовок и параграф).
9. Из текстовых эффектов допускается только тень.
10. Рекомендуется использовать не более 3-4 шрифтовых семейств. При этом, все они должны сочетаться друг с другом.
11. Запрещён набор прописного текста. Для этого существуют программные свойства (Uppercase)
12. Нежелательно использовать прозрачность для элементов содержащих текст, если в этом есть необходимость запрещено делать прозрачность через opacity.

## <a name="Адаптивный-дизайн"></a>Адаптивный дизайн

1. Следует предусматривать 3 основных размера экранов основных устройств:
   1. < 768px — Смартфон. Рекомендуется создавать макет шириной от 320 до 375 пикселей, содержащий 4 колонки с отступами между друг другом от 16 до 24 пикселей
   2. < 1024px — Планшет в портретном режиме. Рекомендуется создавать макет шириной от 768 до 960 пикселей, содержащий 8 колонок с отступами между друг другом в от 24 до 32 пикселей
   3. 1120 > — Компьютер или планшет в альбомном режиме. Рекомендуется создавать макет шириной от 1120 пикселей, содержащий 12 колонок с отступами между друг другом в 32 пикселя
2. Чаще всего для создания всех адаптивных макетов достаточно лишь нескольких страниц (главной и типовой), либо описания.
3. Основные разрешения экранов: 1280, 1366, 1440, 1680, 1920. Не имеет смысла делать разные макеты для 1280 и 1366.

## <a name="Статьи-и-видео-по-теме"></a>Статьи и видео по теме

- [Требования к PSD-макетам](https://github.com/andrey-hohlov/psd-templates-requirements)
- [О чём должен помнить веб-дизайнер](https://github.com/nicothin/web-design)
- [О чём смеются верстальщики | Вадим Макеев | Дизайн-форум Prosmotr](https://www.youtube.com/watch?v=lW4uzJp6uIg)
- [Дизайнь как верстальщик](https://habrahabr.ru/post/311800/)
- [Требования к дизайн-макету сайта - Студия ПаЛыЧа](http://palpalych.ru/blog/7-prochee/85-trebovanija-k-dizajnmaketu-sajta.html)
- [Работа в команде. Как помирить дизайнера и верстальщика](https://habrahabr.ru/post/330144/)
