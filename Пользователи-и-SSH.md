# HQ_SRV и BR_SRV

Сделать на HQ_SRV и на BR_SRV.

Создаем пользователя sshuser.

`useradd sshuser -u 1010 -U` - создание пользователя

`passwd sshuser` - задать пароль пользователю

`вводим пароль пользователя` - P@ssw0rd

`повторяем ввод пароля` - P@ssw0rd

Далее, при необходимости, устанавливаем sudo.

`apt install sudo -y`

Заходим в `visudo` и прописываем нашего пользователя.

![image](https://github.com/user-attachments/assets/24bb4e8f-abcb-41b8-ba85-8c66d1a563d0)



