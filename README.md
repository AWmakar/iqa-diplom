# Курсовой проект к модулю «Ручное тестирование веб-приложений»

Перед вами курсовой проект по модулю «Введение в тестирование». Он содержит задания, которые помогут ещё раз отработать полученные знания и вспомнить теорию. У этого задания более высокий уровень сложности, чем у предыдущих домашних заданий, но оно позволит вам погрузиться в процессы, которые ожидают вас при устройстве на работу и при выполнении рабочих задач.

## Правила выполнения курсового проекта

1. Объект тестирования: интернет-магазин https://henderson.ru. **Важно:** это реальный сайт, не тестовый, поэтому не надо совершать на нём покупки и прочие подобные действия. При возникновении вопросов по работе сайта и связанным проблемам писать надо вашему курсовому руководителю, а не представителям сайта.
1. Скопируйте шаблон таблицы на свой Google Диск [здесь](https://docs.google.com/spreadsheets/d/1Nl2_n46HvTIdv7JpbNLjOtMcWSuYpblZjyxlsBFKanY/edit?usp=sharing), укажите в названии файла свои фамилию, имя и группу вместо Name, Surname, Group. 
1. Проверьте настройки доступа — необходимо, чтобы в ваших документах и таблицах была открыта возможность комментировать всем пользователям в интернете, кому предоставлена ссылка.
1. В предоставленном шаблоне есть все шаблоны, которые нужны для выполнения задания.
1. В своей таблице прикрепляйте ссылки на выполненную работу по каждому заданию.
1. Все таблицы должны быть отформатированы с переносами и правильной вёрсткой, иначе они будут возвращены на доработку. Пример можно увидеть [тут](https://docs.google.com/document/d/1yDj9YWZ6wF7v8edq_aJkSFR9g7QgUil5yuuZgbHDzvE/edit?usp=sharing).
3. Вам необходимо выполнить пять заданий, кроме заданий со звёздочкой (задания 3.2.* и 2.2.* выполняются по желанию).
4. Когда выполните все пять заданий, прикрепите в личном кабинете ссылку на свою таблицу с решениями и ожидайте проверки преподавателя.
5. Курсовой проект считается принятым, когда все пять заданий (кроме заданий 3.2.* 2.2.*) приняты преподавателем.
6. Если вам вернули курсовую на доработку:
- для заданий 1, 2.1., 3.1. доработанную версию надо создать на новом листе в изначальной таблице. Для этого мы [переименовываем](https://drive.google.com/file/d/1dGqZztwZjqlzu-4uyl170akGAfci59N7/view?usp=sharing) уже существующий лист в «ДЗ Версия 1», создаём новый через [дублирование](https://drive.google.com/file/d/1Ich_S9DlpeaQ0BBnalVf-Ip9grsOKESj/view?usp=sharing), новый лист переименовываем в «ДЗ Версия 2» и выполняем доработки уже в нём. Аналогично для доработок после второй;
- для остальных заданий добавляем новую информацию в старом файле или так, как будет согласовано с проверяющим преподавателем;
- доработка по курсовому проекту отправляется студентом и проверяется преподавателем только после доработки всех необходимых пунктов.

## Задание 1

Написать чеклист для функциональной проверки [личного кабинета зарегистрированного авторизованного пользователя](https://henderson.ru/cabinet/), включая функционал разделов, на сайте https://henderson.ru/.

**Требования к выполнению**
* Чеклист должен представлять собой структурированный многоуровневый список, который содержит набор функциональных позитивных и негативных проверок клиентской стороны компонентов объекта тестирования.
* Каждый пункт проверки в должен быть в отдельной ячейке списка и со своим приоритетом.
* При составлении списка проверок должны учитываться различные варианты состояний страниц. Например, при проверке функции «Мои отзывы» мы проверяем не только состояние без отзывов, но и с ними.
* Мы ожидаем от вас список проверок функционала личного кабинета без учёта хедера и футера страницы, то есть то, что есть в этой [области](https://drive.google.com/file/d/1rn6z04Erx7QjUmmTm4-R5MNNBgXpRSP2/view?usp=sharing).

## Задание 2

2.1. Необходимо написать набор тест-кейсов на проверку функционала восстановления пароля.

Ваша задача — написать минимум 20 тест-кейсов, которые должны покрывать всё, что описано в требованиях по
[ссылке](https://docs.google.com/document/d/12deDbATIy0Xps8MiWvumNqHISfAlFc4etY8F4lPcqJ4/edit?usp=sharing), учитывать позитивные и негативные кейсы и включать в себя полные циклы восстановления пароля.
Помните, что мы проверяем не только и не столько саму форму, сколько процесс восстановления с применением техник тест-дизайна.
Обратите внимание, что основа для написания тестов — информация в требованиях, а не на реальном сайте. К тому же сейчас не все требования можно реализовать на реальном сайте.

2.2.*  Напишите свои вопросы по этим требованиям. Они могут касаться не описанных, но важных сценариев, граничных значений и подобных проблем, по аналогии с ДЗ.

## Задание 3

3.1. На основе [скриншота](https://drive.google.com/file/d/1ucv3JFqEGY7ijVtP0Qn0BrdV2ipqYu37/view?usp=sharing) создайте не менее трёх баг-репортов. Обратите внимание, что здесь в окружении мы можем описать тот браузер, с которого проводилась бы проверка, то есть ваш актуальный.

3.2.* Найдите баг в функции «Написать отзыв» в карточке товара и составьте на него баг-репорт. Если найдёте несколько — замечательно!

## Задание 4

Вы тестируете страницу карточки товара. Из ТЗ вы знаете, что товар может стоить от 1 рубля до 10 000 000 рублей. К сожалению, на сайте сейчас товаров с такой ценой нет, а разработчик бэкенда в отпуске, поэтому вам нужно протестировать вёрстку страницы карточки товара с максимальной и минимальной ценой самостоятельно.
Ваша задача — самостоятельно определить, как проще это сделать, и предоставить решение в виде скриншотов страницы карточки товара с минимальной и максимальной ценой. Важно, чтобы было видно, с помощью чего вы изменили эту цену.

## Задание 5

Бэкенд-разработчик говорит, что мы отправляем данные с сайта в неправильном формате, и просит вас помочь найти нужный запрос. Фронтенд-разработчик ушёл в отпуск в поход без связи, а документация пропала.

Известно, что проблема в данных, которые уходят в POST запросе по адресу, который начинается с https://api.mindbox.ru/. Происходит это, скорее всего, при работе с личными данными пользователя, например, авторизацией, личным кабинетом, просмотром корзины.

Ваша задача — изучить ответы и запросы при работе с сайтом, найти запрос, в котором есть нужные параметры, найти, как же выглядят параметры deviceUUID, requestID и status, и приложить скриншот искомого превью в таблицу с решениями.

Обратите внимание, что задание надо выполнять с выключенным VPN и выключенными блокировщиками рекламы.

### Как правильно задавать вопросы преподавателю

Что поможет решить большинство частых проблем:

1. Попробуйте найти ответ сначала самостоятельно в интернете или в материалах курса и только после этого спрашивать у преподавателя. Навык поиска ответов пригодится вам в профессиональной деятельности.
1. Если вопросов больше одного, то присылайте их в виде нумерованного списка. Так преподавателю будет проще отвечать на каждый из них. 
1. При необходимости прикрепите к вопросу скриншоты и стрелочкой покажите, где не получается. 

Что может стать источником проблем:

1. Вопросы вида «Ничего не работает. Не запускается. Всё сломалось». Преподаватель не сможет ответить на такой вопрос без дополнительных уточнений. Цените своё время и время других.
2. Откладывание выполнения курсового проекта на последний момент.
3. Ожидание моментального ответа на свой вопрос. Преподаватели — работающие QA, которые занимаются, кроме преподавания, своими проектами. Их время ограничено, поэтому постарайтесь задавать правильные вопросы, чтобы получать быстрые ответы :)
