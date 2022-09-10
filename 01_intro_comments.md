# Системы контроля версий

Системы контроля версий — инструменты для отслеживания изменений файлов и упрощения совместной работы нескольких разработчиков над одним проектом.
Мы в курсе изучаем систему контроля версий git. Она эффективно работает с текстовыми файлами. Программный код состоит из текстовых файлов. 

## О командной строке

С прогарммами можно взаимодействоать разными способами. Простейший с технической точки зрения — текстовый через так называемый интерфейс командной строки (cli).
Программа git имеет интерфейс командной строки, поэтому необходимо понимать как работать в командной строке. Практика работы в командной строке может
отличаться в различных операционных системах, мы будет использовать в качестве основы командную строку linux. В современных графических оболочках операционных 
систем обычно запускают программу терминала, которая эмулирует консоль (командую строку). Выполенение команд происходит в программной оболочке (shell) внутри консоли.
Существуют различные командные оболочки, мы будем использовать bash. 

## О git

git может следить за изменениями в любом каталоге. Для этого он создаёт специальное хранилище внтури каталога для слежения. 
Каталог для слежения называют рабочим каталогом. Рабочий каталог вместе с хранилищем называют репозиторием. Хранилище обычно содержится в подкаталоге .git.

Процесс работы с репозиторием можно разделить на 2 части:

1. Локальная работа
2. Синхронизация

К локальной работе относят добавление файлов в репозиторий, удаление файлов из него, переключение между изменениями, просмотр разницы между изменениями и другое.
К синхронизации относят отправку изменений в другой репозиторий и выкачивание изменений оттуда.

История изменений может быть нелинейной: git позволяет создавать отдельные ветки развития рабочего каталога. Это позволяет вести параллельную работу 
над одним проектом нескольким разработчикам, а также эффективно прототипировать различные подходы при реализации проекта.

Команды git можно посмотреть в документации. В слайдах лекции приведены некоторые демонстрации базовой работы с git.