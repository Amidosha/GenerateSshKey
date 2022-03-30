1. В командной строке введите следующее: **ssh-keygen -t ed25519 -C "ваш email"** и нажмите Enter
2. На вопрос ```Enter file in which to save the key:``` нажмите Enter
   ![Terminal](/src/img/passware.jpg)
3. На вопрос ```Enter passphrase (empty for no passphrase):``` нажмите Enter
   ![Terminal](/src/img/passware.jpg)
4. На вопрос ```Enter same passphrase again:``` нажмите Enter
   ![Terminal](/src/img/passware.jpg)
5. Набираем в терминале **cd .ssh** нажимаем Enter
6. Набираем в терминале **notepad id_ed25519.pub** нажимаем Enter открывается блокнот с вашим SSH ключом выделяем всю строку и копируем (Правой кнопкой мыши - копировать)
   ![SSHkey](/src/img/SSHkey.jpg)

#### Оглавление

1. [Открытие командной строки](/src/md/Open_CMD.md)
2. [Генерация и копирование SSH ключа в Git](/src/md/Generate_Copy_key.md)
3. [Добавление ключа в Git и клонирование проекта через SSH](/src/md/CloneProjectSSH.md)
