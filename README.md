2.1. Подготовка 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/025d700f-88a3-4eaf-8e3a-c6c34c21a62e" />

2.2.1. Создайте текстовый файл data.txt со строками: 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a10b9eb3-3263-4062-84dd-79615acb52b3" />

2.2.2. Выведите содержимое data.txt на экран с помощью cat. 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/783382e9-6458-4388-8b04-ee3272673183" />

2.2.3. Запишите вывод команды ls -l в файл list.txt 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/25bc2c01-758f-4e4a-9fa8-1ffd47cb9cbe" />

Выполните команду ls /nonexistent. Перенаправьте только stdout в out.txt, а 
stderr – в err.txt: 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e94a3cf0-a313-49c0-89aa-55ba17c67441" />

2.2.5. Используя grep, отфильтруйте из data.txt строки, содержащие "a", и запишите 
результат в filtered.txt:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d9c14244-74c0-40d3-9c23-3fa4b56bdb19" />

2.2.6. С помощью >> добавьте в filtered.txt строку "grape 15": 
echo "grape 15" >> filtered.txt
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5953d33a-ebc9-4e4d-a8cb-393759bf63c6" />

2.3.1. Запустите оболочку sh (sh). Выполните echo $SHELL. Попробуйте 
перенаправить ошибки, как в задании 1.4 (в sh синтаксис &> может не 
работать – используйте 2>). Выйдите из sh (exit). 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ed31d0b6-6b72-4a36-b822-c02288cee84e" />

2.3.2. Запустите zsh. Выполните echo $SHELL. 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/dbe27164-104b-408e-a1be-a4eab02bdf9d" />

2.3.2.1. Создайте временный алиас ll='ls -la' и проверьте его. 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/12e065e1-a71b-4452-9dfe-13986c7ae618" />

2.3.2.2. Создайте переменную окружения export MY_VAR="hello from zsh".
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6f942b9e-8927-49fd-bc9e-3721867eb7d4" />

2.3.2.3. Запустите bash из zsh и проверьте видимость переменной (echo 
$MY_VAR). Выйдите из bash и из zsh.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/670b81b0-5703-456a-b35e-432da7f13e62" />

2.3.3. Запустите fish. 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b94f0e20-2c84-46f6-85ff-bed8a8e817ab" />


