pwd # показать текущий каталог
ls # список файлов в текущем каталоге
ls -la # подробный список, включая скрытые файлы
cd /path/to/dir # перейти в каталог
cd .. # перейти на уровень выше
cd ~ # перейти в домашний каталог

mkdir newdir # создать каталог
mkdir -p a/b/c # создать вложенные каталоги
touch file.txt # создать пустой файл
cp file.txt copy.txt # копировать файл
cp -r dir1 dir2 # копировать каталог рекурсивно
mv file.txt /tmp/ # переместить файл
mv old.txt new.txt # переименовать файл
rm file.txt # удалить файл
rm -r dir # удалить каталог рекурсивно
cat file.txt # вывести содержимое файла
less file.txt # постраничный просмотр файла
head -n 10 file.txt # первые 10 строк
tail -n 10 file.txt # последние 10 строк
tail -f log.txt # следить за файлом в реальном времени

find /path -name "*.go" # найти файлы по имени
grep "pattern" file.txt # найти строки по шаблону
grep -r "pattern" ./dir # рекурсивный поиск по каталогу
grep -i "pattern" file.txt # поиск без учёта регистра

command > file.txt # записать вывод в файл (перезапись)
command >> file.txt # дописать вывод в файл
command < file.txt # передать файл на вход команде
command1 | command2 # конвейер: вывод первой команды – вход второй

chmod 755 script.sh # rwxr-xr-x
chmod +x script.sh # добавить право на выполнение
chmod -R 644 ./dir # рекурсивно установить права
chown user:group file # сменить владельца и группу

ps aux # список всех процессов в ОС Linux
top # интерактивный монитор процессов
htop # улучшенная версия top
kill PID # завершить процесс по PID
kill -9 PID # принудительно завершить процесс
jobs # список фоновых задач
command & # запустить команду в фоне

ip addr # информация о сетевых интерфейсах
ping host # проверить доступность узла
curl http://example.com # выполнить HTTP-запрос
wget http://example.com/file # скачать файл
ss -tuln # список открытых портов
