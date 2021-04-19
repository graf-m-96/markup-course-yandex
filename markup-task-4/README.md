forked from [urfu-2017/markup-task-4](https://github.com/urfu-2017/markup-task-4)

# Задача «Мяндекс.Муррркет»

Перед выполнением задания внимательно прочитайте:

- [О всех этапах проверки задания](https://github.com/urfu-2017/guides/blob/master/workflow/overall.md)
- [Как отправить пулл](https://github.com/urfu-2017/guides/blob/master/workflow/pull.md)
- [Как пройти тесты](https://github.com/urfu-2017/guides/blob/master/workflow/test.md)
- Правила оформления [JavaScript](https://github.com/urfu-2017/guides/blob/master/codestyle/js.md), [HTML](https://github.com/urfu-2017/guides/blob/master/codestyle/html.md) и [CSS](https://github.com/urfu-2017/guides/blob/master/codestyle/css.md) кода

## Основное задание

:warning: Задание необходимо решить __без использования JS и flex/grid__ (если вы знаете, что это)

У моей бабуленьки очень много котиков (=^･ｪ･^=), обычно она как-то «справлялась»
с этим, но потом доброта взяла верх: она подошла к внучку с просьбой помочь.
И так как «яжпрограмист», я предложил ей запустить интернет-магазин добрых котиков.

Название-то нашлось сразу – «Мяндекс.Муррркет». А вот с вёрсткой проблемы,
да и дизайнера нет. Макеты дизайна я решил взять с одного известного магазина
(картинки кликабельны).

На среднем экране:  
<a href="https://cloud.githubusercontent.com/assets/357689/10816073/f482985c-7e51-11e5-8dcb-bcc832f80e86.png" target="_blank">
    <img src="https://cloud.githubusercontent.com/assets/357689/10816073/f482985c-7e51-11e5-8dcb-bcc832f80e86.png" width="300">
</a>

На большом:  
<a href="https://cloud.githubusercontent.com/assets/357689/10816080/fefe442a-7e51-11e5-805a-e9f4ba9274e6.png" target="_blank">
    <img src="https://cloud.githubusercontent.com/assets/357689/10816080/fefe442a-7e51-11e5-805a-e9f4ba9274e6.png" width="300">
</a>

Эти макеты демонстрируют поведение блоков-карточек котиков.
При растягивании экрана количество вмещаемых в строку котиков увеличивается,
при уменьшении, соответственно, уменьшается.

Плюс возможность посмотреть в виде списка:  
<a href="https://cloud.githubusercontent.com/assets/357689/10817444/9dc17254-7e5b-11e5-93e7-943e04381ef6.png" target="_blank">
    <img src="https://cloud.githubusercontent.com/assets/357689/10817444/9dc17254-7e5b-11e5-93e7-943e04381ef6.png" width="300">
</a>

Будет любезно с вашей стороны помочь бабуленьке сверстать магазинчик по этим
макетам. Только не забывайте, что магазин о котиках (=｀ω´=), а значит нужно
найти картинки с котиками и информацию о них (не меньше 10 котиков).

Карточка должна содержать фоточку и некоторую информацию о котике:

* Имя котика (ссылка)
* Категория котика (понятия не имеем что это)
* Уровень доброты котика по 5-бальной шкале (как звёздочки на макетах)
* Стоимость котика (и старая стоимость, если она есть)
* Описание котика

От вас дополнительно требуется:

* Обрезать длинные имена котиков (=^ ◡ ^=)
* Реализовать переключатель вывода котиков: плитками или списком
* Реализовать эффекты при наведении на имя котика, фото,
  категорию, и плитку в целом

### Дополнительное задание (+54 к мурчанию)

:warning: Задание необходимо решить __без использования JS и flex/grid__ (если вы знаете, что это)

Внимательные верстальщики заметили, что в макете используется интересное выравнивание
по нижней линии фоточки котика <(￣︶￣)>	. То есть все карточки выровнены так, что нижние границы
их изображений находятся на одной линии друг относительно друга. Будет здорово, если вы
реализуете и это поведение.

А еще будет ощутимо фантастически, если вы сможете научить шкалу доброты
работать так: при наведении курсора на шкалу, пользователь
выбирает количество звезд, которые он хочет поставить (обратите внимание, что есть
оценка в ползвезды), а по клику шкала запоминает его оценку.

![](https://cloud.githubusercontent.com/assets/357689/19887293/6a45aa1a-a049-11e6-8f02-56d8d5815873.jpg)