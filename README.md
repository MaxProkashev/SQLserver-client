# SQLserver-client
 Клиент сервер c++ на win
 1. клонируйте репозиторий на пк
 2. скомпилируйте файлы командами: 
             g++ main.cpp -l "ws2_32" -o main \n
             g++ client.cpp -l "ws2_32" -o client
 3. запустите сервер main.exe
 4. введите количество начальных элементов дерева (генирируются случайные name phone group)
 5. запустите client.exe (проверьте что он подключился к серверу "CONNECT...")
 6. в клиенте можно использовать такие имитации запросов:
             print - печатает дерево
             end - завершает как клиент так и сервер
             search where name=.. - (phone=.. group=..) можно комбинировать с or, and сколько угодно раз
             delete where -//- такой же функционал как у search
