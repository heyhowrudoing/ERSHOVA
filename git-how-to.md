## Создание SSH-ключа

1. Откройте Git Bash. Если у вас его нет, установите Git для Windows.

2. Введите следующую команду для создания нового ssh-ключа, заменив вашей почтой:

   ```bash
   ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
3. При появлении запроса "Enter a file in which to save the key," нажмите Enter. Это принимает значение по умолчанию ~/.ssh/id_rsa.

4. Введите фразу-пароль или оставьте поле пустым для ключа без пароля.

Добавление публичного ключа в свой аккаунт на GitHub
Запустите следующую команду, чтобы скопировать SSH-ключ в буфер обмена:

bash
Copy code
clip < ~/.ssh/id_rsa.pub
Зайдите на GitHub, кликните на своем аватаре в правом верхнем углу и выберите Settings.

В боковой панели выберите SSH and GPG keys.

Нажмите New SSH key.

В поле Title введите название для нового ключа.

Вставьте свой ключ в поле Key.

Нажмите Add SSH key.

Клонирование своего нового репозитория на рабочий компьютер
Перейдите в директорию, где вы хотите разместить репозиторий, используя команду cd.

Введите следующую команду для клонирования репозитория, заменив "username" и "repository" на соответствующие значения:

bash
Copy code
git clone git@github.com:username/repository.git
После выполнения этих шагов вы должны быть подключены к вашему репозиторию на GitHub через SSH.

Copy code

Это Markdown-файл, который вы можете сохранить и использовать в качестве справочника.



