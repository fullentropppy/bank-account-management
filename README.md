![Java](https://img.shields.io/badge/Java-24-007396?logo=java)
![Maven](https://img.shields.io/badge/build-Maven-C71A36?logo=apache-maven)
[![Version](https://img.shields.io/github/v/release/fullentropppy/bank-account-management?label=version)](https://github.com/fullentropppy/data-sorter/releases)

# Bank Account Management
Bank Account Management: простое банковское приложение.

## Функционал:
- консольный интерфейс с разделением на страницы;
- поддержка банковских операций: создание/просмотр счетов, пополнение, перевод, снятие наличных;
- вывод информации по всем транзакциям и по транзакциям счета;
- проверка ввода при навигации по страницам и при выполнении банковских операций;
- сохранение и загрузка данных работы приложения (`Users/<UserName>/Documents/BAM/data/`).

## Установка и запуск
**Требования:** Java версии не ниже `24`, Maven не ниже `3.9.9`.

1. Скачать `bam.zip` в разделе `Assets` выбранного релиза и распаковать архив;
2. В Windows: Запустить приложение через `run.bat`;
В других ОС: выполнить в терминале команду: 
```console
java -jar bam.jar
```
