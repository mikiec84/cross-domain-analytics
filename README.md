cross-domain-analytics
======================

Вся настройка производится в config.json:
* apiVersion - версия Measurement Protocol API
* hostname - адрес сервера Google Univesal Analytics (для отправки данных через ssl нужно указать https://ssl.google-analytics.com)
* path - URL для запросов
* projects - масив проектов для сбора аналитки
  * projectPreffix - имя проекта (используется как префикс для имени куки)
  * image - путь к картинке (копирайту)
  * UA - идентификатор отслеживания в Google analytics
