Реализовать на Си программу, использующую event loop (можно взять любую библиотеку, желательно libev).
На вход программе передают 1 аргумент - номер порта.
На данном порте открыть слушающий TCP сокет, и на все входящие пакеты отсылать их обратно в неизменном виде.
Тестировать функционал можно с помощью telnet.
Компилирование: gcc -o echo echo.c -lev
