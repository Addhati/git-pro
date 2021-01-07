        git init

        [-q | --quiet] [--bare] [--template=<template_directory>]
	    [--separate-git-dir <git dir>] [--object-format=<format>]
	    [-b <branch-name> | --initial-branch=<branch-name>]
	    [--shared[=<permissions>]] [directory]

>       -q --quiet

При иннициализации проекта не выводит никаких сообщений кроме ошибок и предупреждений

>       --bare

Создает только репозиторий без рабочих файлов. Если после опции не указать путь, то проинициализируется в текущую папку.

>       -- -b <branch-name> --initial-branch=<branch-name>
С помощью данной опции можно изменить имя начальной ветки