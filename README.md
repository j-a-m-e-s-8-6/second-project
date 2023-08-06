# A homemade [CRIB](null "ШПАРГАЛКА") to GIT bash CLI/GitHUB GUI `🤖n00b edition`
>+ 1) (листок с подсказками) crib; trot, pony амер.
>+ 2) преимущественно неодобр. (написанный текст устного выступления) written notes pl; prepared text

* VCS - ver control system 
* SCM - Source Control Management
* CLI - command line interface
* GUI - graphic user interface

![Git-Logo-2Color](https://github.com/j-a-m-e-s-8-6/second-project/assets/141525256/ef61fa4c-e12c-48de-a70f-8b84a8b3fd5c)

#### 💡 *Как расшифровывается Git?*
>На английском сленге слово git означает «мерзавец». Но, по мнению Линуса Торвальдса, создателя Git, название может расшифровываться как угодно — в зависимости от настроения пользователя.
>Например, Global Information Tracker — когда у вас всё хорошо и Git работает отлично. ~~А если что-то идёт не так, Git превращается в Goddamn Idiotic Truckload of sh*t.~~  
>`Longman_DOCE5` git /ɡɪt/ BrE Play AmE Play noun {countable} British English spoken not polite
_Date: 1900-2000; Origin: get 'someone born to an unmarried mother' (16-20 centuries), from get 'to beget'_
an offensive word for an unpleasant and annoying person, especially a man:
You miserable git!

---

### ! DOWNLOAD 💻 [CLI Git BASH and GIT-GUI](https://git-scm.com/download/win "official download site") for Win+ =  [_mintty_ GNU GPLv3](http://mintty.github.io)  
Аналоги GitBash : Mercurial, Subversion, BitBucket, SourceTree, GitLab, etc

---

## Первые команды :
* PWD 🟰 __print working directory__
```bash
$ pwd # print working directory
/c/Users/%USERNAME%/dev/git
```
* CD 🟰 __change directory__
```bash
$ cd ~ # change directory to HOME directory {DIR}  
$ cd "Фотографии с дня рождения" # если пробелы в папке ⚠️  
$ cd github/open-source-project # переходим через несколько директорий  
$ cd . # переходим в текущую директорию  
$ cd .. # переходим на уровень выше  
```
* LS 🟰 __list__
```bash
$ ls # list directory contents  
$ ls # вывели список файлов  
file.txt  
photo.png  

$ ls -a # вывели список, в котором отображаются скрытые файлы ., .. и .git  
.  
..  
.git  
file.txt  
photo.png  
```
* TOUCH 🟰 __create__
```bash
$ touch my-new-file.txt # создали файл my-new-file.txt
$ touch ../../file.txt  # на две папки выше  
```
* MKDIR 🟰 __make directory__
```bash
$ mkdir new-dir # make directory = создали директорию new-dir
$ mkdir -p dir1/dir-inside/dir-deeper-inside  
# создали папку dir-deeper-inside в папке dir-inside, которая находится в папке dir1  
```
* CP 🟰 __COPY__  
```bash
$ cp что_копируем куда_копируем  
$ cp index.html src/  
# скопировали index.html в папку src  

$ cp что_копируем что_копируем что_копируем куда_копируем  
$ cp index.html style.css script.js src/  
# скопировали три файла (index.html, style.css и script.js) в папку src  
```
MV 🟰 __MOVE__
```bash
$ mv table.csv ./very-important-files
# сначала указываем имя файла, который хотим переместить, потом путь — куда перемещаем 

$ cd very-important-files
$ ls
table.csv 
# перешли в папку very-important-files и проверили, что всё сработало
```

```bash

```


### * _examples :_  
```bash
$ pwd
/projects # сейчас мы здесь
$ cd github # переходим в папку github
$ pwd
/projects/github # теперь мы здесь!

$ mkdir first-project  
# создали папку
$ touch first-project/data.txt
# создали первый файл
$ touch first-project/table.csv
# создали второй файл

$ cd first-project  
# перешли в директорию
$ cp data.txt ~
# скопировали файл в домашнюю директорию

$ cd ~ # перешли в домашнюю директорию
$ pwd # посмотрели, где мы
/Users/%USER_NAME%
$ ls # файл скопирован, ура!
data.txt
<...>



```


$ cd ~/dev/first-project # перешли в нужную папку  
$ git init # создали репозиторий  

$ cd <папка с репозиторием> # перешли в папку  
$ rm -rf .git # удалили подпапку .git  
