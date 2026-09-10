2.1. Подготовка 
![src1](https://github.com/user-attachments/assets/025d700f-88a3-4eaf-8e3a-c6c34c21a62e)

2.2.1. Создайте текстовый файл data.txt со строками: 
![src1](https://github.com/user-attachments/assets/a10b9eb3-3263-4062-84dd-79615acb52b)

2.2.2. Выведите содержимое data.txt на экран с помощью cat. 
![src1](https://github.com/user-attachments/assets/783382e9-6458-4388-8b04-ee3272673183)

2.2.3. Запишите вывод команды ls -l в файл list.txt 
![src1](https://github.com/user-attachments/assets/25bc2c01-758f-4e4a-9fa8-1ffd47cb9cbe)

Выполните команду ls /nonexistent. Перенаправьте только stdout в out.txt, а 
stderr – в err.txt: 
![src1](https://github.com/user-attachments/assets/e94a3cf0-a313-49c0-89aa-55ba17c67441)

2.2.5. Используя grep, отфильтруйте из data.txt строки, содержащие "a", и запишите 
результат в filtered.txt:
![src1](https://github.com/user-attachments/assets/d9c14244-74c0-40d3-9c23-3fa4b56bdb19)

2.2.6. С помощью >> добавьте в filtered.txt строку "grape 15": 
echo "grape 15" >> filtered.txt
![src1](https://github.com/user-attachments/assets/5953d33a-ebc9-4e4d-a8cb-393759bf63c6)

2.3.1. Запустите оболочку sh (sh). Выполните echo $SHELL. Попробуйте 
перенаправить ошибки, как в задании 1.4 (в sh синтаксис &> может не 
работать – используйте 2>). Выйдите из sh (exit). 
![src1](https://github.com/user-attachments/assets/ed31d0b6-6b72-4a36-b822-c02288cee84e)

2.3.2. Запустите zsh. Выполните echo $SHELL. 
![src1](https://github.com/user-attachments/assets/dbe27164-104b-408e-a1be-a4eab02bdf9d)

2.3.2.1. Создайте временный алиас ll='ls -la' и проверьте его. 
![src1](https://github.com/user-attachments/assets/12e065e1-a71b-4452-9dfe-13986c7ae618)

2.3.2.2. Создайте переменную окружения export MY_VAR="hello from zsh".
![src1](https://github.com/user-attachments/assets/6f942b9e-8927-49fd-bc9e-3721867eb7d4)

2.3.2.3. Запустите bash из zsh и проверьте видимость переменной (echo 
$MY_VAR). Выйдите из bash и из zsh.
![src1](https://github.com/user-attachments/assets/670b81b0-5703-456a-b35e-432da7f13e62)

2.3.3. Запустите fish. 
![src1](https://github.com/user-attachments/assets/b94f0e20-2c84-46f6-85ff-bed8a8e817ab)

2.3.3.1. 
Создайте алиас: alias ll 'ls -la'. 
![src1](https://github.com/user-attachments/assets/ab6d36ab-93d0-4434-ac31-cb87d9455852)

2.3.3.2. 
Создайте переменную окружения: set -x MY_VAR "hello from fish". 
![src1](https://github.com/user-attachments/assets/73da262f-f1c8-47f5-b4b6-40b280a65d56)

2.3.4. Проверьте: echo $MY_VAR. Выйдите из fish
![src1](https://github.com/user-attachments/assets/250ddb32-e561-4936-b452-4de5138368b0)

2.3.5. Сделайте вывод: в чём основные отличия синтаксиса алиасов и переменных 
в bash vs fish? Запишите в отчёт. 
Алиасы. В Bash — простые подстановки без аргументов; в Fish заменены гибкими функциями с поддержкой аргументов.
Переменные. В Bash — классический синтаксис и явный экспорт (export); в Fish — команда set, автоэкспорт и упрощённое обращение.
Философия. Bash придерживается традиционных Unix‑подходов, Fish делает акцент на интуитивность и расширенные возможности

2.4.1. Выполните последовательно три команды через ;: 
echo "First"; echo "Second"; echo "Third" 
![src1](https://github.com/user-attachments/assets/e6abbe1a-535d-4305-9239-6499ea1db011)

2.4.2. Используя &&, создайте файл test.txt и только в случае успеха запишите в 
него "OK": 
![src1](https://github.com/user-attachments/assets/928830b7-d771-4c9f-ac20-b4f26e7dfa1f)

2.4.3. Сымитируйте ошибку: rm notexist.txt || echo "File not found". 
![src1](https://github.com/user-attachments/assets/9032894d-8059-46d0-a712-cdc5b4489947)

2.4.4. Постройте конвейер из трёх команд:
![src1](https://github.com/user-attachments/assets/e6bb1bf1-002b-4285-b58c-8e387714e48e)

2.4.5. Вычислите количество процессов вашего пользователя:
![src1](https://github.com/user-attachments/assets/6174e328-6cec-424c-9d20-2db0909a5d01)

2.5.1. В текущей сессии bash создайте алиас lll='ls -l | grep "^d"'.
![src1](https://github.com/user-attachments/assets/785c7efe-576e-45f6-bac7-6a75e9167510)

2.5.2. Выполните lll в каталоге lab2.
![src1](https://github.com/user-attachments/assets/5d9fb08c-4d0d-4ccc-83a9-9b312ed50e78)

2.5.3. Создайте алиас myip='curl ifconfig.me 2> /dev/null'. 
![src1](https://github.com/user-attachments/assets/e966f398-58ea-4465-8585-a144cac19c6f)

2.5.4. Убедитесь, что после закрытия терминала алиасы пропадут
![src1](https://github.com/user-attachments/assets/52976b71-968b-494b-935a-aa5be28ca471)

2.6.1. Отредактируйте файл ~/.bashrc.
![src1](https://github.com/user-attachments/assets/30795cff-296f-4c5b-85c5-50f5f02c31c8)

2.6.2. Примените изменения: source ~/.bashrc.
![src1](https://github.com/user-attachments/assets/a73c77d8-0a56-4ba8-bbd9-f1d74978ff4f)

2.6.3. Проверьте работу алиасов: up (можно отменить Ctrl+C), myip.
![src1](https://github.com/user-attachments/assets/566b87cf-3d94-4267-b9c7-c3b4f7359825)

2.6.4. (Для zsh пропишите аналогичные алиасы в ~/.zshrc, для fish – в 
~/.config/fish/config.fish с синтаксисом alias up "sudo apt update && sudo apt 
upgrade -y").
![src1](https://github.com/user-attachments/assets/59c83107-7720-4589-a2fe-0b6da89a6abc)
![src1](https://github.com/user-attachments/assets/e01f7013-f4b5-4603-9dfc-bb881f44f306)

2.7.1. В bash создайте локальную переменную TEMP_VAR="temporary". 
![src1](https://github.com/user-attachments/assets/b058e99a-97af-440c-a641-4ef14f4be5ee)

2.7.2. Выполните echo $TEMP_VAR.
![src1](https://github.com/user-attachments/assets/10512f3a-1ba7-4eda-9ccd-6663fb2fde5d)

2.7.3. Запустите bash (дочерняя оболочка) и попробуйте вывести echo $TEMP_VAR. 
Объясните результат.
![src1](https://github.com/user-attachments/assets/19cf9a28-8015-459e-bdd8-05d809c0d698)

2.7.4. Выйдите из дочерней оболочки (exit). Создайте экспортируемую 
переменную: 
export GLOBAL_VAR="exported" 
![src1](https://github.com/user-attachments/assets/23ef0d36-1025-491a-b452-98e5cc1f1d74)

2.7.5. Запустите bash и проверьте echo $GLOBAL_VAR. 
![src1](https://github.com/user-attachments/assets/cb690adc-4acd-4c12-a730-240dd82d1f31)

2.7.6. Удалите переменную: unset GLOBAL_VAR. 
![src1](https://github.com/user-attachments/assets/645e028c-774a-407b-81e9-f54dfdc94b82)

2.8.1. Добавьте в ~/.bashrc строку: 
export EDITOR="nano" 
![src1](https://github.com/user-attachments/assets/5c58611c-6a07-4a99-b41f-bbefa9d2ac01)

2.8.2. Выполните source ~/.bashrc
![src1](https://github.com/user-attachments/assets/1fcb52b8-b0aa-48a4-8cf5-52b2baaf6c7a)

2.8.3. Проверьте: echo $EDITOR. 
![src1](https://github.com/user-attachments/assets/8ef12775-9796-4134-b3e8-c24e7e1aeb05)

2.8.4. Добавьте также export WORKSPACE="$HOME/lab2".
![src1](https://github.com/user-attachments/assets/4b2bd881-5933-445c-b138-0ebd5630a483)

2.8.5. Проверьте, что после перезапуска терминала эти переменные остаются.
![src1](https://github.com/user-attachments/assets/12f2c37a-b209-4874-bed0-ed991f62e381)

2.9. Комплексный скрипт (закрепление) 
Напишите скрипт на bash (файл lab2_script.sh) со следующим функционалом: 
![src1](https://github.com/user-attachments/assets/1aa59ade-c259-4cab-9391-949301bb06b4)

2.9.1. Скрипт принимает один аргумент – имя файла. 
2.9.2. Проверяет, передан ли аргумент; если нет – выводит сообщение об ошибке в 
stderr и завершается с кодом 1. 
2.9.3. Создаёт временную переменную окружения BACKUP_TIME с текущей 
датой. 
2.9.4. Создаёт каталог backup в $HOME/lab2, если его нет. 
2.9.5. Копирует переданный файл в каталог backup с добавлением суффикса .bak. 
2.9.6. Записывает в файл backup/log.txt строку вида: YYYY-MM-DD HH:MM:SS - 
скопирован файл <имя> в <путь к бэкапу> (использовать echo и 
перенаправление >>). 
2.9.7. Выводит сообщение об успехе в stdout. 
![src1](https://github.com/user-attachments/assets/8ab6ff93-f812-4b6a-824f-3ba25c418b9a)
![src1](https://github.com/user-attachments/assets/6f2d83e9-f077-42c8-9ff6-2c84ee9a2f6b)
![src1](https://github.com/user-attachments/assets/874c3f3d-2140-4871-8cbb-c7a4ce07b18f)

4. Контрольные вопросы

4.1. > — перезаписывает файл, >> — дописывает в конец.



4.2. ; — выполняет команды подряд, && — вторая выполняется только при успехе первой.



4.3. Объединить stdout и stderr: команда > файл 2>&1 или команда &> файл (Bash/Zsh).



4.4. Алиас — псевдоним для команды. Постоянный: в Bash — в .bashrc, в Zsh — в .zshrc, в Fish — через abbr или в config.fish.



4.5. export делает переменную доступной для дочерних процессов. Постоянная — через добавление export VAR=value в конфигурационный файл оболочки.



4.6. Просмотр переменных окружения: env или printenv.



4.7. Передача вывода одной команды на ввод другой: через конвейер |.



4.8. Fish vs Bash: в Fish алиасы — через функции/abbr, переменные задаются через set



4.9. Перенаправление stdin из файла и stdout в другой: команда < input.txt > output.txt. Для stderr — 2> error.txt или 2>&1


