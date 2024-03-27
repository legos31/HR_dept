Установка
------

Подготовьте файлы по примеру имеющихся дистрибутивов:

```
config/db.php
web/index.php
web/index-test.php
tests/codeception/config/config.php
```

Создайте рабочую и тестовую базы данных и сконфигурируйте подключение к ним в `db.php` и `config.php`.

Выполните миграции:

```
php yii migrate
```

Для запуска тестов выполните инструкции в файле `tests/README.md`.
