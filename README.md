<b>Запуск скрипта через index.php</b>


<p>Все параметры задаются в файле params.php</p>

<b>MAKE</b> - Задается в формате "Lexus, Honda, и т д" регистр роли не играет
<b>MODELS</b> - Модели задаются в аналогином формате
<b>MILLEAGE</b> - Пробег задается числом (км) с разницей в +/- 20000 км. Например если задать 100000 - выборка будет проводиться по интервалу от 80000 км до 120000 км
<b>GEARBOX</b> - Коробка передач 1 - Механическая, 2 - Автоматическая
<b>YEAR</b> - Год задается с интервалом в 2 года. Например: 2018 - будет производить поиск в интервале от 2016г. до 2018г.



<p>Все идентификаторы хранятся в data.json. Если нужно можно обновить скриптом update_data_json.php, также если нужно можно настроить авттобновление идентификаторов через crontab</p>