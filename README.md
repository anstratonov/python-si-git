# Шаблон приложения для летнего интенсива

## Технологии

* [Flask](http://flask.pocoo.org/)
* [Bootstrap](https://getbootstrap.com)

## Инструкция

* Установка зависимостей
```
pip install -r requirements.txt
```

* Запуск веб-сервиса
```
export FLASK_ENV=development
flask run
```

## Ветки

* (?) hello - helloworld для демонстрации
* (?) templates - hello с шаблонами
* base - базовая версия
* db - версия с подключенной базой данных
* tests - версия, покрытая тестами

## Ключевые моменты

* Запуск приложения
  * Зависимости
  * Переменные окружеия
  * DEBUG mode
  * Логи
* Структура приложения
* От адресной строки до результата
* Отладка
  * Принтами
  * Фласк-дебаггер
* Шаблоны
* Bootstrap
* Формы

## Обязательные темы по коре

* import
* функции
  * создание, использование
  * области видимости
  * func(func2(something))
* list
  * append
  * reversed
  * list of dict
* dict
  * создание
  * доступ по ключу
* декораторы
* datetime
