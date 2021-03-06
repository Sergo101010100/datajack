# Datajack
[![Build Status](https://travis-ci.org/sbtqa/datajack.svg?branch=master)](https://travis-ci.org/sbtqa/datajack) [![GitHub release](https://img.shields.io/github/release/sbtqa/datajack.svg?style=flat-square)](https://github.com/sbtqa/datajack/releases) [![Maven Central](https://img.shields.io/maven-central/v/ru.sbtqa.tag.datajack/datajack-parent.svg)](https://search.maven.org/search?q=g:ru.sbtqa.tag.datajack%20AND%20a:datajack-parent&core=gav)

DataJack - opensource java framework, который позволяет вам комфортно работать с вашими тестовыми данными.

### О DataJack
DataJack имеет две фичи:
* **Stash** - класс, который можно использовать для хранения и использования данных во время выполнения тестов.
* **TestDataProvider** - интерфейс, который используется для работы с различными хранилищами тестовых данных.   
Сейчас поддерживаются следующие типы хранилищ:
  * [JSON-Provider](https://github.com/sbtqa/datajack/tree/master/providers/json-provider)
  * [Properties-Provider](https://github.com/sbtqa/datajack/tree/master/providers/properties-provider)
  * [Mongo-Provider](https://github.com/sbtqa/datajack/tree/master/providers/mongo-provider)
  * [Excel-Provider](https://github.com/sbtqa/datajack/tree/master/providers/excel-provider)

### Документация
Проект с примером использования можно посмотреть [здесь](https://github.com/sbtqa/datajack-example) и [здесь](https://github.com/sbtqa/datajack/tree/master/providers/json-provider/src/test).

### Контакты
Нашли ошибки или появились вопросы? [Проверьте](https://github.com/sbtqa/datajack/issues), нет ли уже созданных задач. Если нет, то создайте [новую](https://github.com/sbtqa/datajack/issues/new)!

### Лицензия 
Datajack выпущен под лицензией Apache 2.0. [Details here](https://github.com/sbtqa/datajack/blob/master/LICENSE).
