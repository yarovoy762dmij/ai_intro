[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yarovoy762dmij/ai_intro/blob/main/lab1/notebooks/lab1.ipynb)

| | VS Code | Colab |
|---|---|---|
| Версия Python | 3.13.7 | 3.13.18 |
| Версия pandas | 3.1.1 | 2.2.3 |
| Где хранятся файлы | Локально на компьютере | В репозитории на гитхабе, запускается облачно |
| Что потребовалось для запуска | VS Code, расширения Python и Jupyter, выбор ядра интерпретатора | Аккаунт Google, репозиторий GitHub |

# Практическое занятие 1. Рабочее окружение

Автор: Яровой Дмитрий Михайлович, группа 251-952

## Структура папки lab1

Папка data содержит данные, папка notebooks – ноутбук lab1.ipynb, файл requirements.txt – список библиотек.

## Запуск на локальном компьютере

В папке lab1:

1. Создать окружение: python -m venv .venv
2. Включить окружение: .venv\Scripts\activate (macOS и Linux: source .venv/bin/activate)
3. Установить библиотеки: pip install -r requirements.txt
4. Открыть notebooks/lab1.ipynb в VS Code и выбрать ядро .venv
