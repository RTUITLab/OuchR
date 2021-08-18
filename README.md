# OuchR

Проект, позволяющий автоматизировать работу HR специалистов, организуя общение кандидатов через бота ВКонтакте.

Текущая архитектура представлена на следующей диаграмме:

![текущая архитектура](readme/current_architecture.png)

Состояние реализации архитектуры на данный момент (18.082021)

| Сервис                                  | Репозиторий                                                    | Развернуто                          | CI                                 |
| --------------------------------------- | -------------------------------------------------------------- | ----------------------------------- | ---------------------------------- |
| Панель пользователя/администратора      | [OuchR-Site](https://github.com/RTUITLab/OuchR-Site)           | <span style="color:green">Да</span> | <span style="color:red">Нет</span> |
| Основная система                        | [OuchR-Bot](https://github.com/RTUITLab/OuchR-Bot)             | <span style="color:green">Да</span> | <span style="color:red">Нет</span> |
| Источники вакансий                      | <span style="color:red">Нет</span>                             | <span style="color:red">Нет</span>  | <span style="color:red">Нет</span> |
| Анализ резюме на соответствие вакансиям | [OuchR-PdfParser](https://github.com/RTUITLab/OuchR-PdfParser) | <span style="color:red">Нет</span>  | <span style="color:red">Нет</span> |
| Проверка результатов                    | <span style="color:red">Нет</span>                             | <span style="color:red">Нет</span>  | <span style="color:red">Нет</span> |
| Message bus                             | -                                                              | <span style="color:red">Нет</span>  | <span style="color:red">Нет</span> |
