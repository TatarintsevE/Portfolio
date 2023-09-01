# Портфолио: QA Engineer

## Обо мне 

Привет! Меня зовут Егор, я начинающий тестировщик. <br>
В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.
<br>

## Навыки и технологии
``Jira``,``Qase.io``,``SQL``,`` Postman``,``Mockoon``, ``Swagger``, ``Trello``, <br>
``SoapUI``, ``pgAdmin 4``, ``Confluence``, ``PICT``, ``Notion``, ``Sitechco``, ``Chrome DevTools``.




## Проекты

<p> Проект 1: протестировать кабинет учителя Skyeng</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>1️⃣ сделать тест-план,</li>
  <li>2️⃣ подготовить тестовую документацию,</li>
  <li>3️⃣ провести тестирование,</li>
  <li>4️⃣ написать отчет о результатах тестирования.</li>
</ol>

<p>Как решала(-а): краткое описание решения (автореферат)<p>

Первым делом я ознакомился с ``Документацией к проекту``, чтобы понять как должен работать функционал. > <a href="https://skyengpublic.notion.site/6746e543d02c43879de0057cafe196b0">Ссылка на документацию</a>
Далее я проанализировал ``Требования стейкхолжеров`` ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/4a5e5272-8521-4947-9942-b3c46c76b24d), послего чего сформировал приемочные ``Тест-кейсы`` ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/baed8a1b-b481-44ab-9189-cad6912feca4)
Провел ``Тестирование требований`` ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/48a08297-91e4-422c-b5a4-150fbc64bfe2)
Составил ``интеллект-карту функционала "Личные события"`` > <a href="https://miro.com/app/board/uXjVMNzYLF4=/?share_link_id=951381061491">Ссылка на документацию</a>
Прописал ``Тест-план``.
Далее подготовка ``Тестовой документации``. Составил функциональный чек-лист для новой функции (личные события) ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/873780cb-66ec-4185-b952-9b19d50d95e4)
Составил ``тест-кесы для Smoke-тестирования`` ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/d7375b8e-3c6e-4eba-a289-88d6845ce135).

Начинаем проводить тестирование. 
Smoke-тестирование: ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/5c60ba80-502d-4a4b-b262-70e0daf28659)
Функциональное тестирование: ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/f946f572-7363-478c-89b0-f1a6fa12a94c)  ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/e8aaa23c-ce15-43ec-8c7b-54f80c17372b)  ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/d56ec51e-bb9a-41aa-86c6-9bfe7a95cfca)  ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/5fbc46b7-c24d-4a4c-a75b-f7f815466a89)  ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/72842f34-55c5-4bb6-b0f4-ecd0e02d8790)  ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/2a1072a4-731c-4b4f-ab6c-63e4964773de)  ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/c12ff974-be8b-4f16-bcc9-6fd24d1994b9)
Регрессионное тестирование: ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/f5ca34b0-7c9b-4abf-8dcc-1c4d8c6e8c32)  ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/fe0716c5-e320-424f-af64-35a67f833d73)
Приемочное тестирование: ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/d2b209ad-924b-441d-9f2c-34145096cb1c)

По найденым багам были заведены баг-репорты в Jira.
![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/8e6e7c6c-ec9d-4a5a-89d2-323ebf14f4e0)
![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/5c5f2850-7c1d-417c-8f0b-03d45406c008)

Последним действием мною были описаны отчеты по результатам тестирования.
 
 <p>Выводы (итоги):<p>
<ol>
  <li>Рекомендации
1) Основная рекомендация как можно быстрее исправить все найденные баги с Серьезностью S1 Blocker в функционале “личные события”. Распределить баги согласно приоритету и серьезности для быстрого исправления.
2)На мой взгляд, продукт (портал) на данный момент запускать нецелесообразно, т.к. в системе “личные события” есть недоработки, требующие исправления. Требуется небольшая доработка и исправление багов по основной функциональности. 
3)Решить все вопросы с требованиями. Организовать общий грумминг.</li>
  <li>Метрики
Рекомендованные к использованию метрики:
1)``Коэффициент стабильности требований.`` Требования часто меняются, возникает достаточно много вопросов к ним. Требуются глобальные переделки. Данная метрика поможет улучшить работу с требованиями.
2)``Плотность дефектов.`` Данная метрика поможет выделить часть системы с наибольшим количеством дефектов. Благодаря чему, мы сможем уделить больше внимания в разработке и тестировании этой системы.</li>
</ol>


<br> 

<p> Проект 2:  протестировать кабинет учителя Skyeng</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>1️⃣ сделать тест-план,</li>
  <li>2️⃣ подготовить тестовую документацию,</li>
  <li>3️⃣ провести тестирование,</li>
  <li>4️⃣ написать отчет о результатах тестирования.</li>
</ol>

<p>Как решала(-а): краткое описание решения (автореферат)<p>

``По сути мы берем прошлый проект, только к нему добавляется еще тестирование API.``

Первым делом я ознакомился с ``Документацией к проекту``, чтобы понять как должен работать функционал. > <a href="https://skyengpublic.notion.site/6746e543d02c43879de0057cafe196b0">Ссылка на документацию</a>
Далее я проанализировал ``Требования стейкхолжеров`` ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/4a5e5272-8521-4947-9942-b3c46c76b24d), послего чего сформировал приемочные ``Тест-кейсы`` ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/baed8a1b-b481-44ab-9189-cad6912feca4)
Провел ``Тестирование требований`` ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/48a08297-91e4-422c-b5a4-150fbc64bfe2)
Составил ``интеллект-карту функционала "Личные события"`` > <a href="https://miro.com/app/board/uXjVMNzYLF4=/?share_link_id=951381061491">Ссылка на документацию</a>
Прописал ``Тест-план``.
Далее подготовка ``Тестовой документации``. Составил функциональный чек-лист для новой функции (личные события) ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/873780cb-66ec-4185-b952-9b19d50d95e4)
Составил ``тест-кесы для Smoke-тестирования`` ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/d7375b8e-3c6e-4eba-a289-88d6845ce135).

Начинаем проводить тестирование. 
Smoke-тестирование: ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/5c60ba80-502d-4a4b-b262-70e0daf28659)
Функциональное тестирование: ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/f946f572-7363-478c-89b0-f1a6fa12a94c)  ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/e8aaa23c-ce15-43ec-8c7b-54f80c17372b)  ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/d56ec51e-bb9a-41aa-86c6-9bfe7a95cfca)  ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/5fbc46b7-c24d-4a4c-a75b-f7f815466a89)  ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/72842f34-55c5-4bb6-b0f4-ecd0e02d8790)  ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/2a1072a4-731c-4b4f-ab6c-63e4964773de)  ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/c12ff974-be8b-4f16-bcc9-6fd24d1994b9)
Регрессионное тестирование: ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/f5ca34b0-7c9b-4abf-8dcc-1c4d8c6e8c32)  ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/fe0716c5-e320-424f-af64-35a67f833d73)
Приемочное тестирование: ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/d2b209ad-924b-441d-9f2c-34145096cb1c)

По найденым багам были заведены баг-репорты в Jira.
![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/8e6e7c6c-ec9d-4a5a-89d2-323ebf14f4e0)
![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/5c5f2850-7c1d-417c-8f0b-03d45406c008)

``Приступаем к части работы со вторым проектом``
Приступаем к ознакомлению новой ``Документации к проекту``. > <a href="https://skyengpublic.notion.site/1-cd209a4dbeef4ccf9f8b9449b20eb497">Ссылка на документацию</a>
Затем составляю ``функциональные тест-кейсы`` ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/98139436-6cd3-43b5-9a86-6428f96f9c07)
На основе данных тест-кейсов создаю Postman коллекцию и провожу тестирование ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/dbfc5791-3ee4-45fe-8f40-427bd763c64a)  ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/b3ed4938-f6f7-48f6-ab6a-58766a27328b)  ![image](https://github.com/TatarintsevE/Portfolio/assets/143797418/aa57d367-6c45-4885-8fd2-de22e0dc9bd6)
Затем отчет по результату тестирования.

 <p>Выводы (итоги):<p>
<ol>
  <li>Рекомендации
1)Основная рекомендация как можно быстрее исправить все найденные баги с Серьезностью S1 Blocker в функционале “личные события”. Распределить баги согласно приоритету и серьезности для быстрого исправления.
2)На мой взгляд, продукт (портал) на данный момент запускать нецелесообразно, т.к. в системе “личные события” есть недоработки, требующие исправления. Требуется небольшая доработка и исправление багов по основной функциональности.
3)Решить все вопросы с требованиями. Организовать общий грумминг.
4)Дополнительно мною было проведено тестирование API с помощью инструмента Postman.  Все запросы через метод POST функционируют корректно. Есть одно исключение: единственный запрос - создание личного события без названия, отображается с ошибкой. Исходя из документации проекта, это адекватная реакция, т.к. поле “Название” обязательно к заполнению.  В целом, система работает исправно.</li>
  <li>Метрики
Рекомендации к использованию метрики:
1)``Коэффициент стабильности требований.`` Требования часто меняются, возникает достаточно много вопросов к ним. Требуются глобальные переделки. Данная метрика поможет улучшить работу с требованиями.
2)``Плотность дефектов.`` Данная метрика поможет выделить часть системы с наибольшим количеством дефектов. Благодаря чему, мы сможем уделить больше внимания в разработке и тестировании этой системы.</li>
</ol>


## Контактная информация
- Email: tatarintsevjegor@yandex.ru
- LinkedIn: https://www.linkedin.com/in/username/
- Личный сайт: https://t.me/champagnechampi
