# RozovoePoniCTF

Разработка RP CTF <3

## Структура

```
rozovoeponictf/
    \_ category-5e-suffixes/ (category=категория, 5=Номер задания из категории, e=уровень сложности (easy, medium, hard), suffixes=Название задания)
        \_ deploy
        |   \_ category-5e-suffixes
        |       \_ (файлы для раскатки на серваки - Dockerfile, docker-compose.yaml, ...)
        \_ ctfd
        |   \_ task.conf (файл с названием задания, стоимостью, флагом, описанием, прикреплемыми файлами)
        \_ give
        |   \_ (файлы для раскатки на серваке)
        \_ dev
        |   \_ (разработческие файлы, промежуточные, неготовые)
        \_ solution
        |   \_ writeup.md (райтап)
        \_ heartbeat
        |   \_ heartbeat.conf (конф файл для сервиса heartbeat - проверки сервиса на активность)
        \_ exploit
            \_ exp.py (эксплоит на задание)


[First story](https://medium.com/@special_gerl771/analysis-of-destructive-malware-whispergate-targeting-ukraine-e2c72676199f)
```
