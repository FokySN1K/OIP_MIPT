Как создать ssh-ключ:
ssh-keygen -t rsa -b 4096 -C "your_email"

Как добавить ключ в аккаунт на GitHub:
копируем содержимое cat /.ssh/id_rsa.pub
добавляем это в раздел SSG GitHub-a


Как склонировать репозиторий:
git clone git@github.com:FokySN1K/OIP_MIPT.git