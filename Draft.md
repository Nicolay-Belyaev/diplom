# Цель проекта
Получить сайт, через который можно будет продавать услуги инструктора по сноуборду (что бы не стыдно было давать на него ссылки).

Основаная причина выбора такой темы проекта - мне действительно хочется и было бы полезно иметь такой сайт, а значит - проще не потерять мотивацию.
# Задачи проекта
Сайт должен обладать следующими свойствами:
- адаптивность;
- легкость;
- минимализм в дизайне;
- отсутствие решений, нарушающих интеллектуальные права;

и содержать следующие страницы и формы:
- Главная страница, содержащая ссылки на другие разделы Сайта и дополнительную информацию, позволяющему Пользователю сделать однозначный вывод о тематике и содержании Сайта.
- Форма подачи заявки на обучение, позволяющий принять у Пользователя обязательную для меня информацию: имя, фамилия, телефон Пользователя. Кроме того, страница с формой должна производить расчет стоимости занятия исходя из того, какое количество часов занятий в каком периоде желает забронировать Пользователь.    
<возможно, какой-то еще функционал, который я придумаю по ходу>
- Интерактивный календарь, показывающий пользователю доступные для бронирования дни и часы занятий. Дополнительным преимуществом календаря будет отображение периодов с высокими и низкими ценами на занятия.
- Форма отправки видео для разбора мною ошибок в катании Пользователя. Должна содержать, собственно, саму форму, поле для комметария пользователя и поле для моего отзыва.
- Страница для размещения текстовых заметок о технике катания. Должна корректно показывать текст и фото/видео. Желательно, иметь фукционал удобного добавления/редактирования текста.
- Страница с информацией об услугах и ценах.
- Страница с контактными данными.
- Страница с FAQ.

# Критерии достижения цели и задач проекта
- К сайту имеется доступ через Интернет.
- адаптивность: сайт корректно отображается на устройствах с разными размерами экрана/использующими разные браузеры.
- легкость: при стабильном соединении время полной загрузки Главной страницы составляет не более 2 секунд (лучше - меньше 1). Время загрузки сложных форм не более 4 секунд.
- минимализм в дизайне: сайт использует простую графику, минимум анимаций, корректно работает даже если графические элементы вообще не загрузились (например, если картинки были удалены с сайта или у пользователя медленный интернет).
- отсутствие решений, нарушающих интеллектуальные права: сайт сделан мною самостоятельно, сторонние решения лицензированы для свободного использования в коммерческих целях либо на них приобретены права использования в коммерческих целях (но лучше бы такие штуки сделать самому, учимся не для того что бы покупать софт, а что бы его создавать).
- на сайте присутствуют и работают как описано выше все страницы и формы.
# Технологии
Гугл подсказывает, что существует 3 подхода к сайтстроению:
1. Писать всё с нуля на каком-то чистом языке программирования. Полная свобода действий, но и всю работу придется делать самому. 
Хорошо, если надо делать что-то суперуникальное и/или высоконагруженное. Мой проект точно НЕ суперуникальный и скорее всего не будет высоконагруженным.
Пишут на всем, Python, PHP, Java, JS, C# и наверное все остальные широко известные ЯП. Кусочки больших проектов могут быть написаны на разных ЯП.
2. Использовать какой ЯП + фреймворк к нему. Фреймворк - это набор правил и готовых инструментов для чего-то, например, разработки сайта. Свободу ограничивает, но упрощает жизнь. Нормальный вариант для проектов средней сложности. 
Часто встречал такие комбинации: Python + Django, Java + Spring, Ruby + Ruby on Rails, JS + Node.js, тысячи их.
Выглядит как мой вариант. 
3. Использовать "конструктор сайтов", такие штуки еще называются CMS. Писать самому или не надо ничего вообще, или самый минимум. Сильнее всего режут свободу творчества. Подходят для стандартных проектов, вроде сайтов-визиток, лендингов и и прочих простых штук. Сейчас у меня крутится сайт на CMS Wordpress. Если хочется сделать что-то, что не реализовано в "стандартных шаблонных конструкциях" - то это прям боль, работать нормально скорее всего не будет. Все самые интересные штуки - за отдельные бабки. Не мой выбор.

А вообще, написать бы все на Dart+Flutter. Работать будет сразу везде и на всем.