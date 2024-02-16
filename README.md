# 7-01
### Задание 1
Какие преимущества даёт подход IAC?
1. скорость
2. воспроизводимость
3. масштабируемость
4. не нужна ручная настройка

### Задание 2
Выполните действия и приложите скриншоты действий.
1. Установите Ansible.
2. Настройте управляемые виртуальные машины, не меньше двух.
3. Создайте файл inventory с созданными вами ВМ.
4. Проверьте доступность хостов с помощью модуля ping.


![image](https://github.com/AnastasiyaEvsseva/7-01/assets/151757353/abe3c661-8cc9-41c9-91b9-4f2170c07377)

![image](https://github.com/AnastasiyaEvsseva/7-01/assets/151757353/9861b9f3-6817-435e-a036-f16c044b226f)

и sudo service ssh restart .
На host0: ssh-copy-id vagrant@192.168.33.11; ssh-copy-id vagrant@192.168.33.12

![image](https://github.com/AnastasiyaEvsseva/7-01/assets/151757353/a2db416f-9893-4cb9-a34d-562d3d20c780)

![image](https://github.com/AnastasiyaEvsseva/7-01/assets/151757353/c6b9ed74-3b4e-43f3-8811-d9cb59b7d6da)


![image](https://github.com/AnastasiyaEvsseva/7-01/assets/151757353/d265e1ca-d115-458a-b88e-db5f91cc66cc)



### Задание 3
Какая разница между параметрами forks и serial?
forks - максимальное количество одновременных подключений, выполняемых Ansible для каждой задачи.
serial - определяет количество узлов, обрабатываемых в каждой задаче за один запуск.

### Задание 4
Выполните действия и приложите скриншоты запуска команд.

Установите на управляемых хостах любой пакет, которого нет.
Проверьте статус любого, присутствующего на управляемой машине, сервиса.
Создайте файл с содержимым «I like Linux» по пути /tmp/netology.txt.

![image](https://github.com/AnastasiyaEvsseva/7-01/assets/151757353/ec556ea2-7989-46d9-a064-7b6828681388)
![image](https://github.com/AnastasiyaEvsseva/7-01/assets/151757353/cfc358ce-f3c5-497e-9b75-2617a9178fc3)
![image](https://github.com/AnastasiyaEvsseva/7-01/assets/151757353/b776be6b-efde-43ed-947d-ea3da8ff9342)
![image](https://github.com/AnastasiyaEvsseva/7-01/assets/151757353/3bf973b6-60be-4de4-af12-30cb00411f57)
![image](https://github.com/AnastasiyaEvsseva/7-01/assets/151757353/ab7a655f-41cf-41bd-8e05-f6563d7914a9)







