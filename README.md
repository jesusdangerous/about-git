Version Control System - это программное обеспечение, которое помогает отслеживать изменения в программах, текстовых файлах, больших документах, веб-сайтах и так далее.


Одно изменение или группу изменений в VCS называют ревизией или версией.

Команды Git:

$ pwd (print working directory) - вывести путь к текущей директории.<br />
$ cd  (change directory) - изменить директорию.<br />
$ ls (list directory contents) - отобразить содержимое директории.<br />
$ mkdir - создать директорию.<br />
$ cp (copy) - скопировать файлы.<br />
$ mv (move) - переместить файлы.<br />
$ rm (remove) - удалить файлы.<br />
$ rm -r - удалить файлы рекурсивно.<br />
$ git init - создать репозиторий.<br />
$ git status - посмотреть статус репозитория.<br />
$ git add - добавить файлы в репозиторий.<br />
$ git commit - создать коммит.<br />
$ git log - посмотреть историю коммитов.<br />
$ git remote add - привязать удаленный репозиторий к локальному.<br />


```mermaid
graph LR;
  untracked -- "git add" --> staged;
  staged    -- "???"     --> tracked/comitted;

%% стрелка без текста для примера: 
  A --> B;
``` 