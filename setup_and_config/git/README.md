    git

######

        --version

Показывает текущую установленную версию гита `git --version`

       --help

Показывает краткий обзор и наиболее используемые команды
- -a --all - показывает все доступные команды `git --help --all`
- <команда> показывает помощь по конкретной команде. Может ставиться до или после опции `git --help status`
######

        -C <path>

Позволяет запустить любую команду гит по указанному пути
`git -C ~/projectname/ status`

        -c <name>=<value>

Можно захардкодить значение для конфига для текущей команды  `git -c user.name=yourName commit`

        --html-path --man-path --info-path

Выводит пути нахождения различной документации по git `git --html-path`

       -p --paginate
Принудительно указывает вывод информации через less `git -p`

       -P --no-pager
Показывает весь вывод сразу `git -P`

       --git-dir=<path>
Хардкодит путь к папке репозитория для текущей команды `git --git-dir=./yourDir`

       --work-tree=<path>
Хардкодит путь к рабочей папке для текущей команды `git --work-tree=./yourDir`
