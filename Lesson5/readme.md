### Tasks description for Lesson 5:

#### Комментарии:

Задание к уроку 5 выполнено.

Мне показалось неправильным создание нескольких копий ConnectionString в разных классах; дублирование одной и той же константы в разных местах, по-моему - верный путь к ошибкам. Поэтому я решил описать ее один раз в Startup и передавать в конструкторы репозиториев. Но столкнулся с проблемой передачи параметров в конструктор при создании объектов через DI; я нашел в Интернете решение, но не уверен, что оно идеально.

В качестве счетчиков производительности я выбрал
Processor / % Processor Time
ASP.NET Applications / Errors Total
LogicalDisk / % Free Space
Web Service / Current Connections
Memory / Available MBytes

Остальное сделано в соответствии с методичкой.
Контроллеры для возврата нужной информации из базы данных модифицировать не понадобилось - это уже было сделано ранее.