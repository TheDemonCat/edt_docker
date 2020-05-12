# Образ c 1С:Enterprise Development Tools

## Сборка 

1. Создать файл `.env` в корне проекта. В качестве примера использовать `.env.example`. В файле должны быть определены переменные:
```
    ONEC_USERNAME=<ПОЛЬЗОВАТЕЛЬ_USERS.1C.V8.RU>
    ONEC_PASSWORD=<ПАРОЛЬ_ОТ_USERS.1C.V8.RU>
    ONEC_VERSION=8.3.14.1993
    ONEC_PG_VERSION=9.6-2-1C
    VERSION_EDT=2020.2.0_350
```
2. Запустить сборку образа с помощью скрипта

```
    ./make.sh
```

