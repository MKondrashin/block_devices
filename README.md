
1. Запустить первый раз vagrant up завершится с ошибкой SATA controller уже существует
2. Запустить второй раз vagrant up. Будут созданы контроллеры и диски. Диски будут присоеденены к контроллерам.

Скрипт для создания массива в mdadm_create.txt
Конфиг для mdadm в mdadm.conf
Так же fstab с примонтированной к массиву ФС.
Пробовал создавать файлы в /mnt и перезагружать VM - файлы были доступны после перезагрузки.