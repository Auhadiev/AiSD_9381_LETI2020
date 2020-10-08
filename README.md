# AiSD_9381_LETI2020
Репоизторий для лабораторных работ по АиСД группы 9381
# Правила работы с репозиторием
   ● Для начала работы нужно сделать форк этого репозитория и скопировать его себе на компьютер

   ● Для каждой лабораторной создаётся своя отдельная ветка c названием в формате <Surname\lab#>

   ● Работать следует строго в своей директории Surname/

   ● Для каждой работы создаётся отдельная директория lab#, где # - номер лабораторной

   ● При внесении локальных изменений следует работать со своим форком репозитория

   ● Внутри папки с названием должны находиться материалы, определяемые преподавателем, который будет проверять работу

   ● Файл отчёта должен содержать в своём названии фамилию студента, "АиСД" и № ЛР (например: "ИвановИ.И.АиСД_ЛР1.odt")


# Сдача и защита работ:
1. Сдача:

   1.1. Студент передаёт преподавателю материалы (отчёт и материалы, необходимые для запуска), загружая их в репозиторий*. Если это исправления в текущем пул-реквесте, то студент оставляет соответствующий комментарий (например, "Исправлено").

   1.2. Преподаватель проверяет материалы, оставляет замечания.

2. Защита: студент отвечает на вопросы по видеосвязи (возможно, с демонстрацией работы программы). Перед защитой студент должен показать зачётную книжку с фотографией.

Оба этапа могут повторяться.

---

   [*] Для загрузки лабораторной работы в репозиторий следуте создать pull-request из своей ветки с лабораторной работой в master-ветку общего репозитория. Заголовок пул-реквеста следует оформлять в формате <lab# - Фамилия>. В описании к пулл-реквесту дописать номер выбранного варианта.

   Каждый студент сдаёт каждую работу конкретному преподавателю. Распределение определяется по таблице: https://docs.google.com/spreadsheets/d/1RNcHyfMh-SAdNf-H7XlLcLTXH2jbWkJ4xZ6cyiemIk4/edit#gid=237704424 (лист с буквой "р" в названии).

   ФМА – Фирсов Михаил Александрович

   ЕАА – Ерёменко Анна Александровна

   ЧАА – Чиронова Анастасия Александровна

   # Сдаваемые материалы по лаб. работам:
   ● Фирсов Михаил Александрович:

   ○ отчёт;

   ○ Файлы для запуска:

     а) exe-файл, запускаемый в Windows 7 SP1 x64 (+ файлы, необходимые для запуска, если такие есть);
 
     б) либо файл с кодом + файл со ссылкой на онлайн-компилятор, в котором можно этот код запустить;

   ○ файл с указанием того, что необходимо установить в системе для запуска (если требуется; например, версия MS Visual Studio Redistributable);

   ○ файл с примером входных данных.

   ● Ерёменко Анна Александровна:

   - отчёт;

   - ?

   ● Чиронова Анастасия Александровна:

   - отчёт;

   - ?

   # Правила дистанционной проверки:
   ● Работа не проверяется, попытка не снимается и пул-реквест студента получает метку "Требуются исправления перед проверкой", если:

   - Не выполнены правила работы с репозиторием;

   - В отчёте нет титульного листа, задания, номера варианта или исходного кода;

   - Выбран недопустимый (несуществующий или занятый) вариант;

   - Не удаётся запустить программу.

   Преподаватель оставляет в комментарии к пул-реквесту причину.

   ● Работа не проверяется, пул-реквест студента получает метки "Требуются исправления перед проверкой" и "п1", если:

   - Номер варианта в отчёте не соответствует заданию;

   - Код в отчёте неполный или не соответствует программе.

   Преподаватель оставляет в комментарии к пул-реквесту причину.

   ● После проверки работы преподаватель:

   - Оставляет в комментарии к пул-реквесту нумерованный список недостатков, при этом номера недостатков, исправление которых нужно только для плюсиков, берутся в скобки;

   - В том же комментарии указывает, на сколько очков зачтена работа и какие плюсики получены (например: "Зачтено на 3 очка, +а+ф+к+у.").

   - Ставит на пул-реквест метку "п#", где # - номер попытки сдачи данной работы студента, начиная с 1. Метка не ставится (попытка не снимается), если студент имел зачёт на 3 или более очков и в данной попытке исправлял только плюсики.

   - Ставит на пул-реквест метку "Зачтено <3 очков", "Зачтено ≥3<4 очков" или "Зачтено 4 очка", в зависимости от количества очков. Если набрано 0 очков, то метка о зачёте не ставится. Если количество очков увеличилось, то неактуальная метка о зачёте снимается.

   - Записывает в таблице (https://docs.google.com/spreadsheets/d/1RNcHyfMh-SAdNf-H7XlLcLTXH2jbWkJ4xZ6cyiemIk4/edit#gid=1249381768 , лист "9381") № варианта, очки и плюсики по работе ГОЛУБЫМ ЦВЕТОМ. Если в ЛР3 или ЛР4 использовались шаблоны (template), то это отмечается в столбце "t".

   ● После защиты работы преподаватель:

   - Оставляет в комментарии к пул-реквесту запись о защите работы, указывая, на сколько очков защищена работа (обычно это число не может быть больше, чем количество очков, на которое зачтена работа).

   - Ставит на пул-реквест метку "z#", где # - номер попытки защиты данной работы студента, начиная с 0.

   - Ставит на пул-реквест метку "Защищено <3 очков", "Защищено ≥3<4 очков" или "Защищено 4 очка", в зависимости от количества очков. Если набрано 0 очков, то метка о защите не ставится. Если количество очков увеличилось, то неактуальная метка о защите снимается.

   - Если работа защищена на положительное количество очков, то перезаписывает в таблице (https://docs.google.com/spreadsheets/d/1RNcHyfMh-SAdNf-H7XlLcLTXH2jbWkJ4xZ6cyiemIk4/edit#gid=1249381768 , лист "9381") набранные очки и перекрашивает данные в ЧЁРНЫЙ ЦВЕТ.

   - В конце, если работа защищена на максимальное количество очков и получены все плюсики, то пул-реквест закрывается.

   ● Пул-реквесты студентов не добавляются в главный репозиторий (не выполнять Merge).
