    git

    [--version] [--help] [-C <path>] [-c <name>=<value>]
    [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
    [-p|--paginate|-P|--no-pager] [--no-replace-objects] [--bare]
    [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
    [--super-prefix=<path>]
        <command> [<args>]

##### Опции

        --version

Показывает текущую установленную версию гита

       --help

Показывает краткий обзор и наиболее используемые команды
- -a --all - показывает все доступные команды
- <команда> показывает помощь по конкретной команде. Может ставиться до или после опции
######

        -C <path>

Позволяет запустить гит по указанному пути

        -c <name>=<value>

Можно захардкодить значение для конфига

        --html-path --man-path --info-path

Выводит пути нахождения различной документации по git

       -p --paginate
Принудительно указывает вывод информации через less

       -P --no-pager
Показывает весь вывод сразу

       --git-dir=<path>
Хардкодит путь к папке репозитория отличный от .git

       --work-tree=<path>
Хардкодит путь к рабочей папке