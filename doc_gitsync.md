## Инициализация гитсинха (один раз)

gitsync init -u gitbot D:\Storages1C\DemoTest\ D:\Git\DemoTest\src\cf\

## Синхронизация с хранилищем

gitsync plugins enable sync-remote

gitsync plugins sync-remote --help

gitsync sync -u gitbot D:\Storages1C\DemoTest\ D:\Git\DemoTest\src\cf\
gitsync sync -G -P -u gitbot D:\Storages1C\DemoTest\ D:\Git\DemoTest\src\cf\