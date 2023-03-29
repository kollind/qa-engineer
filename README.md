# Обо мне:
Мое портфолио QA инженера и примеры выполненных работ/тестовых заданий за время обучения:

Тестирование API:

- **CRUD Collection + json scripts in tests.postman_collection.json** – _полный цикл питомца в API (создание, получение информации, продажа, удаление) + автотесты в Postman (парсинг тела ответа, получение, запись в окружение и сравнение значений ключей, проверка наполнения тела ответа)_

- **Json_sendRequest.postman_collection.json** – _отправка PUT запроса через JSON скрипт (также может использоваться для тестирования регистрации с уже имеющимся email'ом, отправляем POST запрос на сервер с регистрацией пользователя, скриптом прописываем внутри него еще один POST запрос и получаем сразу две регистрации на одной почте, чтобы даже в пустой БД проверить регистрацию с уникальным почтовым ящиком)_

Тестовые артефакты: 

- **Применение техник тест-дизайна.xlsx** – _задача из курсов на применение различных техник тест-дизайна_
- https://docs.google.com/spreadsheets/d/1ItlU7QzcWxLrxjCxPnLGwMThpb45VH2U9hf3wa85QGw/edit#gid=0 – _тестовое задание, пример написания тест-кейсов и плана тестирования_


СУБД:

- **Запросы и подзапросы PostgreSQL (Работа с БД).sql** – _базовые запросы SQL, вывод данных из таблицы, задача с обучения_


Подготовка базы для автотестов (обучению питону, после чего перейду к пониманию CSS и Selenium):
- https://replit.com/@kollind – Продолжаю обучение Python для развития навыков автотестировщика, на реплите собираю решенные задачи
- https://replit.com/@kollind/PUBGGunsrandomizer#pyproject.toml — В ходе обучения решил параллельно реализовывать программу для друзей.
Суть — составлять сценарий для игры в PUBG. На данный момент реализован только рандомайзер оружий:
  Вводим количество игроков, вводим имена, вводим карту, на которой будет идти игра (чтобы добавить в пул оружий уникальные для карт). Игрокам присваиваются случайные значения из списка (с этим оружием они будут играть на очередной карте). По окончании игры указываем значение взяли топ1 или нет, если да, то в зависимости от выживших к концу игры пополняется баланс игроков, который они могут тратить на рерол.
Типы данных для управления программой:

{
  "Какой режим запускать?": int // от 1 до 2 для выбора из доступных режимов, 2й еще очень сырой
  "Сколько игроков?": int //от 1 до 4 по размеру группы в PUBG
  "Введите имя/никнейм {p+1}-го игрока": "string" //Представляемся программе, чтобы она выдавала сетап оружия и пополняла баланс
  "Какая карта прокнула?": "string" //необходимо для подгрузки уникальных оружий карты в общий список для шафла
  "Желаете потратить очки на рерол?": "+" or "-" //Для подтверждения действия или пропуска. Запускается только если у кого-то из игроков на балансе >= 50 очков
  "Взяли топ-1?": "+" or "-" //Для подсчета статистики побед/поражений и перехода в условный оператор на выдачу очков
  "Сколько выжило?": int //Для выполнения условия оператора if. Проверка все ли игроки дошли до конца
  "Ещё одну?": "+" or "-" //Повтор бесконечного цикла или завершение работы. Т.к. количество игр заранее неизвестно все итерации проходят до завершения работы кода пользователем
}

На данный момент (30.03.2023) я обучаюсь программированию на Python около месяца, поэтому код написание кода далеко от идеала. Не используются названия функций, много хардкода, однако считаю важным выложить отдельный проект, чтобы потенциальный работодатель мог оценить логику мышления, умение работать и обучаться.

В будущем код буду оптимизировать и приводить в порядок по мере получения необходимых знаний. Любая конструктивная критика и обратная связь приветствуются.

Делаю как сайд проект, чтобы закреплять знания, полученные в ходе обучения (отдельно от итоговых работ, которые необходимо будет сдавать на курсе)

Спасибо за внимание, надеюсь вы зайдете по ссылке и попробуете в деле мое приложение.
Хорошего дня!
  
 
