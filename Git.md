# Git - программа для контроля версий

В программировании проблемы совместной работы над проектами возникли ещё до появления облачных сервисов. 

***Git*** — *самая популярная система контроля версий, но не единственная. Алгоритм работы подобных систем схож.*

1. Прежде чем создавать репозиторий и инициализировать Git, проверим текущую установленную версию пограммы. Для этого в терминале введём команду:

**git --version**

2. Инициализация: указываем папку, в которой git начнёт отслеживать изменения:

**git init**

3. Показывает текущее состояние гита, есть ли изменения, которые нужно закоммитить (сохранить):

**git status**

4. Добавляет содержимое рабочего каталога в индекс для последующего коммита. Эта команда дается после добавления
файлов. Писать название целиком не обязательно: терминал дозаполнит данные автоматически:

**git add**

5. Команда git commit берёт все данные, добавленные в индекс с помощью git add, и сохраняет их слепок во внутренней базе данных, а затем сдвигает указатель текущей ветки на этот слепок:

**git commit -m**

6. Перед переключением версии файла в Git используйте команду git log, чтобы увидеть количество сохранений:

**git log**

7. Переключение между версиями:

**git checkout**

8. Для работы нужно указать не только интересующий вас коммит, но и вернуться в тот, где работаем, при помощи команды: 

**git checkout master**

9. Вывод на экран текущей или создание новой ветки:

**git branch**

10. Показывает разницу между текущим файлом и сохранённым:

**git diff**

11. Сливает ветку с текущей:

**git merge**