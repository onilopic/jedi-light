# JediLight

Облегченная версия [пакета](https://github.com/notamedia/console-jedi). Выпилено все, кроме работы с окружением.
Форк [пакета](https://github.com/ProklUng/jedi-light). 

## Зачем?

За два года использования ничего больше из оригинального пакета не понадобилось. Плюс он застыл в развитии, залочившись на 
старые версии компонентов.

## Установка

composer.json:

```json
 "repositories": [
    {
      "type": "git",
      "url": "https://github.com/onilopic/jedi-light"
    }
  ]
```

```bash
composer require onilopic/jedi-light
```

После скопировать файл `jedi` в `php/bin` (если в иное место, то требуется корректировка файла `jedi`).

## Использование

Все согласно документации оригинального пакета.

`php bin/jedi env:init default`

Второй вариант:

`./vendor/bin/jedi env:init default`

Скопирует в `bitrix` все, что лежит в соответствующих папках директории `environments/default`.
