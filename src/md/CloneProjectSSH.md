   1. Открываем [Github](https://github.com/)
   2. Открываем выпадающее меню нажатием на иконку вашего профиля в правом верхнем углу и нажимаем settings 
   ![image](https://user-images.githubusercontent.com/52781072/160904393-e1a61cf4-a32b-4d10-a44e-b13b470df9a8.png)

   4.Открываем вкладку SSH and GPG keys и нажимаем News SSH key
   ![SSHkeyAdd](/src/img/SSHkeyAdd.jpg)
   4.В открывшемся окне пишем в графе Title имя ключа, в графу **key** вставляем наш ключ который мы копировали ранее и нажимаем **Add SSH key**
   ![Addkey](/src/img/Addkey.jpg)
   [Генерация и копирование SSH ключа в Git](/src/md/Generate_Copy_key.md)
   5.Открываем страницу проекта который хотим склонировать в  [Github](https://github.com/)
   6.Нажимаем вкладку **Code** и выбираем **SSH** копируем строчку под
   ![Clone](/src/img/Clone.jpg)
   7.Открываем терминал и пишем git clone и вставляем строчку котруб скопировали с гита 8.Ваш проект склонирован

#### Оглавление

1. [Открытие командной строки](/src/md/Open_CMD.md)
2. [Генерация и копирование SSH ключа в Git](/src/md/Generate_Copy_key.md)
3. [Добавление ключа в Git и клонирование проекта через SSH](/src/md/CloneProjectSSH.md)
