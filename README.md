# ParserNeercIfmo

## Как работать с этой штукой:
1) Пример вызова функций приведен в main.py
2) get_dict_with_links() - возвращает список словарей, где ключи - nameOfSummary(название предмета), linkOfSummary(ссылка на конспект), topicsOfSummary(ссылки на темы)
3) write_to_json("имя_файла", словарь) - записывет в Json словарь
4) get_from_json("имя_файла") - считывает Json файл и возвращает словарь
