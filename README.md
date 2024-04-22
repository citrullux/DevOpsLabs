# Лабораторный курс по дисциплине: Администрирование, сопровождение и DevOPS

Этот файл содержит базовое объяснение и ссылки на задания к лабораторным работам.

Данное руководство опускает вопросы установки ОС на виртуальную машину или в виде WSL. Для получения этой информации будет выпущен отдельный документ.

Для выполнения потребуется доступ уровня sudo. Его наличие можно проверить исполнив команду `$ sudo whoami`. Если ответом будет root, значит у вашего пользователя есть соответствующий доступ.

Все вводимые консольные команды в данном руководстве обозначены знаком `$` для обычного пользователя и `#` для суперпользователя.

Команды для Debian-подобных систем будет иметь обозначение `Debian:`

Команды для RHEL-подобных систем будут иметь обозначение `RHEL:`

То что выполнимо как на Debian так и на RHEL написано в виде

`$ something`

либо

`# something`

в завосомости от необходимых прав.

Если у Вас установлена Arch-подобная система - удачи найти инструкцию на ArchWiki.

Содержимое файлов представлено в виде текста оформленного

```
примерно вот так
```

Дополнительные объяснения в тексте, отмечающие возможные ошибки и методы решения

> оформлены так

Сохранение файлов в `nano` производится комбинацией клавиш `Ctrl+O` после чего вам предлагается ввести имя файла, выход производится комбинацией `Ctrl+X`, если случайно попадёте в Vi/Vim то помните что выход производится комбинацией `Esc -> :wq! -> Enter`

# Лабораторная работа 1: Локальный git.

# Лабораторная работа 2: Введение в github.

# Лабораторная работа 3: Ansible. Примеры использования.

Данная работа показывает основы использования инструмента Ansible.

Ansible позволяет выполнять команды сразу на множестве компьютеров (далее - узлов) находящихся в пределах одной локальной сети.

В ходе работы рассматривается связь узла самого с собой как с узлом сети и выполнение на нём кзаданых команд.

### [Задание](./Lab3/Lab3.md)

# Лабораторная работа 4: CI/CD на примере github actions.

# Лабораторная работа 5: Node Exporter/ Prometheus и Grafana для мониторинга ресурсов.

# Лабораторная работа 6: Веб сервер Nginx в реверс-прокси режиме. Использование Let's Encrypt.

# Лабораторная работа 7: Docker и Kubernetes.