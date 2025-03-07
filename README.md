# Проект мобильного приложения Яндекс.Метро

> - [Требования](https://drive.google.com/file/d/1p6xlO1EcpwuPcFYxGkwguCADuZ0gq1FC/view?usp=sharing) и [макеты(figma)](https://www.figma.com/design/3MYe7Z1o2w7kB2qVqC7sYt/Metro-Dev-(Copy)?node-id=1-767&p=f&t=rmnPRPJRUZDiexpW-0)
> - [текущая версия приложения](https://drive.google.com/file/d/1LY6BMQmh2D6x6QL7y7crqgcrJ93X7pmB/view?usp=sharing)
> - [готовящаяся сборка](https://drive.google.com/file/d/1D5XQRAxXXW-O3RtGYLqLddBW2chxMVS3/view?usp=sharing)


## Задачи

### 1. Подготовка к функциональному тестированию

Написать проверки в форме чек-листа к требованиям, выделенным жирным шрифтом, которые затронул рефакторинг приложения.

### 2. Подготовка к регрессионному тестированию

Написать чек-лист для регрессионного тестирования, который учитывает особенности мобильного приложения.

### 3. Выполнение тестирования

Провести тестирование по подготовленным чек-листам и зафиксировать баг-репорты

### 4. Отчёт о тестировании


## Тестовая документация

**[1. Чек-лист функционального тестирования](https://docs.google.com/spreadsheets/d/1cFHnevFkwZB6M-HVHbWToRrhb8QN3Y2Vgmcdj5lsPd4/edit?gid=899462569#gid=899462569)**

**[2. Чек-лист регрессионного тестирования](https://docs.google.com/spreadsheets/d/1cFHnevFkwZB6M-HVHbWToRrhb8QN3Y2Vgmcdj5lsPd4/edit?gid=1540435533#gid=1540435533)**

**[Баг-репорты](https://docs.google.com/spreadsheets/d/1cFHnevFkwZB6M-HVHbWToRrhb8QN3Y2Vgmcdj5lsPd4/edit?gid=591572137#gid=591572137)**  

**[Карта объектов функционального тестирования (MindMap)](https://xmind.ai/share/7Ld1DK1I?xid=TTH39f1w)**

**[Карта объектов регрессионного тестирования (MindMap)](https://xmind.ai/share/YLkK8HH9?xid=YWrkNde6)**

## Отчёт

Из **50 проверок** успешно прошло **37**, не прошло — **13**

Список багов, найденных при тестировании, разбит по приоритетам:

- Блокирующие: [BUG-8](https://docs.google.com/spreadsheets/d/1cFHnevFkwZB6M-HVHbWToRrhb8QN3Y2Vgmcdj5lsPd4/edit?gid=591572137#gid=591572137&range=9:9), [BUG-12](https://docs.google.com/spreadsheets/d/1cFHnevFkwZB6M-HVHbWToRrhb8QN3Y2Vgmcdj5lsPd4/edit?gid=591572137#gid=591572137&range=13:13)
- Критичные: нет
- Стандартные: [BUG-1](https://docs.google.com/spreadsheets/d/1cFHnevFkwZB6M-HVHbWToRrhb8QN3Y2Vgmcdj5lsPd4/edit?gid=591572137#gid=591572137&range=2:2), [BUG-2](https://docs.google.com/spreadsheets/d/1cFHnevFkwZB6M-HVHbWToRrhb8QN3Y2Vgmcdj5lsPd4/edit?gid=591572137#gid=591572137&range=3:3), [BUG-3](https://docs.google.com/spreadsheets/d/1cFHnevFkwZB6M-HVHbWToRrhb8QN3Y2Vgmcdj5lsPd4/edit?gid=591572137#gid=591572137&range=4:4), [BUG-9](https://docs.google.com/spreadsheets/d/1cFHnevFkwZB6M-HVHbWToRrhb8QN3Y2Vgmcdj5lsPd4/edit?gid=591572137#gid=591572137&range=10:10), [BUG-10](https://docs.google.com/spreadsheets/d/1cFHnevFkwZB6M-HVHbWToRrhb8QN3Y2Vgmcdj5lsPd4/edit?gid=591572137#gid=591572137&range=11:11), [BUG-11](https://docs.google.com/spreadsheets/d/1cFHnevFkwZB6M-HVHbWToRrhb8QN3Y2Vgmcdj5lsPd4/edit?gid=591572137#gid=591572137&range=12:12), [BUG-13](https://docs.google.com/spreadsheets/d/1cFHnevFkwZB6M-HVHbWToRrhb8QN3Y2Vgmcdj5lsPd4/edit?gid=591572137#gid=591572137&range=14:14)
- Желательные: [BUG-4](https://docs.google.com/spreadsheets/d/1cFHnevFkwZB6M-HVHbWToRrhb8QN3Y2Vgmcdj5lsPd4/edit?gid=591572137#gid=591572137&range=5:5), [BUG-5](https://docs.google.com/spreadsheets/d/1cFHnevFkwZB6M-HVHbWToRrhb8QN3Y2Vgmcdj5lsPd4/edit?gid=591572137#gid=591572137&range=6:6), [BUG-6](https://docs.google.com/spreadsheets/d/1cFHnevFkwZB6M-HVHbWToRrhb8QN3Y2Vgmcdj5lsPd4/edit?gid=591572137#gid=591572137&range=7:7), [BUG-7](https://docs.google.com/spreadsheets/d/1cFHnevFkwZB6M-HVHbWToRrhb8QN3Y2Vgmcdj5lsPd4/edit?gid=591572137#gid=591572137&range=8:8)

**С учётом того, что блокирующие баги, не расположены в основных пользовательских сценариях, а критических не найдено, возможно опубликовать новую версию приложения в Google Play до исправления обнаруженных багов**.
