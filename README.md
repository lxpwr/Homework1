# Homework1
Otus homeworrk #1
1. Установлена ОС Centos8 с ядром версии 4.18.0-516.el8.x86_64
[vagrant@lab1-krnl-upd ~]$ uname -r
4.18.0-516.el8.x86_64

2. Выполнено добавление репозитария:
[vagrant@lab1-krnl-upd ~]$ sudo yum install -y https://www.elrepo.org/elrepo-release-8.el8.elrepo.noarch.rpm
3. Выполнено обновление ядра:
[vagrant@lab1-krnl-upd ~]$ sudo yum --enablerepo elrepo-kernel install kernel-ml -y
4. Проверка версии после перезагрузки:
[vagrant@lab1-krnl-upd ~]$ uname -r
6.5.10-1.el8.elrepo.x86_64
