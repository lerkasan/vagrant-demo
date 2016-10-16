Процедура запуска:

0. Установить VirtualBox.

1. Остановить службы Tomcat и Postgres или любые другие службы, которые используют порты 8080 и 5432 (если они у Вас установлены).

2. Выполнить команду git clone https://github.com/lerkasan/vagrant-demo.git

3. В командной строке перейти в папку, в которую git склонировал исходники, а затем в подпаку vagrant-demo/vagrant-demo
Например cd /home/lerkasan/vagrant-demo/vagrant-demo

4. Выполнить в командной строке команду vagrant up

5. Подождать пока скачается и установится Ubuntu и все необходимые пакеты.

6. После того, как в окне консоли появится надпись "==> default: [INFO] Started Jetty Server", можно открыть браузер и зайти на страницу localhost:8080.

7. Для остановки виртуальной машины vagrant-а нажать дважды Ctrl+C в командной строке ;)

или

7а. Открыть новое окно командной строки и перейти в папку vagrant-demo/vagrant-demo

7б. Выполнить в окне из п. 7а команду vagrant halt