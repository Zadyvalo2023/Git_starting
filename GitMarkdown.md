# Работа с Git  и GitHub 
## 1.Проверка наличий установленного Git
в терминале выполнить команду 'git --version'
Если Git  установлен появиться информация о версий программы , иначе будет сообщение об ошибке.
## 2. Установка Git 
Загружаем последнюю версию с сайта 
 https://git-scm.com/downloads
 Устанавливаем настройки по уммаолчанию.
 ## 3. Настройка Git 
 При первом использований Git нещбходимо представиться. Для этого нужно ввести в терминале две команды:
 
 '''
 $ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
'''
## 4 Основные команды 
**git init** - инициализация локального репозитория.<br>
**git status** - получить информацию от git о его текущем состоянии.<br>
**git add** – добавить файл или файлы к следующему коммиту.<br>
**git commit -m “message”** – создание коммита.<br>
**git log** – вывод на экран истории всех коммитов с их хеш-кодами.<br>
**git checkout** – переход от одного коммита к другому.<br>
**git checkout master** – вернуться к актуальному состоянию и продолжить работу.<br>
**git diff** – увидеть разницу между текущим файлом и закоммиченным файлом.<br>
## 4. Инициализация репозитория 
## 5. Запись изменений в репозиторий 
## 6. Просмотр историй комитов 
## 7. Перемещение между сохранениями
## 8. Игнорирование файлов 
 Для того что бы исключить из отслеживание в репозиторий определенные файлы и папки  необходимо создать там файл ***gitignore***  и записать в него их название или шаблоны, соответствующие таким файлам или папкам.
 ## 9. Создание веток в Git 
 По умолчанию имя основной ветки в Git 
 *master* 
 Создать ветку можно командой '''git branch <имя новой ветке>'''
Текущая ветка будет отмечена звездочкой: **\*master**
## 10. Слияние веток в Git.
**git-merge**— объединить две или более истории разработки вместе
''' git merge [-n] [--stat] [--no-commit] [--squash] [--[no-]edit]
	[--no-verify] [-s <strategy>] [-X <strategy-option>] [-S[<keyid>]]
	[--[no-]allow-unrelated-histories]
	[--[no-]rerere-autoupdate] [-m <msg>] [-F <file>]
	[--into-name <branch>] [<commit>…​]
git merge (--continue | --abort | --quit) ''' 
## 11. DESCRIPTION
Incorporates changes from the named commits (since the time their histories diverged from the current branch) into the current branch. This command is used by git pull to incorporate changes from another repository and can be used by hand to merge changes from one branch into another.q
Assume the following history exists and the current branch is "maste:
git frame 
git blame 
git log 
git checkout -b revert 
Забыл добавить сами файлы для синхрона git add 
Теперь тут новый комит ! 