
Министерство образования и науки РФ
Государственное бюджетное профессиональное образовательное учреждение Республики Марий Эл
Йошкар-Олинский технологический колледж

[Описание предметной области](https://github.com/9002015pro/UML/blob/main/README.md#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%B5%D0%B4%D0%BC%D0%B5%D1%82%D0%BD%D0%BE%D0%B9-%D0%BE%D0%B1%D0%BB%D0%B0%D1%81%D1%82%D0%B8). </br>
[USE-CASE](https://github.com/9002015pro/UML/blob/main/README.md#use-case). </br>
[Диаграмма прецендентов](https://github.com/9002015pro/UML/blob/main/README.md#%D0%B4%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0-%D0%BF%D1%80%D0%B5%D1%86%D0%B5%D0%BD%D0%B4%D0%B5%D0%BD%D1%82%D0%BE%D0%B2). </br>

## Курсовой Проект

по дисциплине "Проектирование и дизайн Информационных систем" Тема: "Автосервис"

Разработал: Кириллов Владилен 
Группа: И-31
Преподаватель: Колесников Евгений Иванович
г.Йошкар-Ола, 2021 

# USE CASE
![enter image description here](images/image.bmp)

# Описание предметной области

![enter image description here](https://a-kt.ru/sites/default/files/styles/node_header_picture_lg/public/2019-05/avtoservis.jpg?itok=o3g2krhq)
*Наша компания занимается исключительно предоставлением [услуг автосервиса]*(https://ru.wikipedia.org/wiki/%D0%A1%D1%82%D0%B0%D0%BD%D1%86%D0%B8%D1%8F_%D1%82%D0%B5%D1%85%D0%BD%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%BE%D0%B3%D0%BE_%D0%BE%D0%B1%D1%81%D0%BB%D1%83%D0%B6%D0%B8%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F).
*Реализация предоставления услуг выглядит так:*
  1. Клиент скачивает наше приложение.
 2. Выбирает одну из услуг, допустим "Диагностика ТС"
 3. После он оставляет свои контакты связи(Номер, телефона), которые записываются в базу данных.
 4. Далее эти данные видит наш менеджер и связывается с клиентом обговаривая все нюансы.
 5. Когда клиент привозит свое ТС в авто сервис он может отследить процент выполненных работ у себя в приложении. 


# Диаграмма прецендентов
  

  &nbsp; | &nbsp;
--|------ 
*Имя прецедента* | Прецедент: Выбор услуги
*Идентификатор прецедента* | ID 1
*Краткое описание* | Клиент выбирает услугу в приложении
*Акторы, вовлеченные в прецедент* | Главные акторы:<br/>Клиент<br/>
*Состояние системы на начало прецедента* | Предусловия:<br/>нет
*Фактические этапы прецедента* | Основной поток:<br/>1. Прецедент начинается, когда Клиент выбирает услугу<br/>2. Если Клиент выбирает услугу в приложении у которого есть дополнительные услуги<br/>&nbsp;&nbsp;&nbsp;&nbsp;2.1 <br/> 3. Если Клиент выбирает товар которого нет в наличии<br/>&nbsp;&nbsp;&nbsp;&nbsp;3.1 
*Альтернативные потоки* | Альтернативные потоки:<br/>2.1 <br/>3.1 
*Состояние системы после окончания прецедента* | Постусловия<br/>1. Клиент выбрал услугу<br/>2. Клиент отказался от услуги 


