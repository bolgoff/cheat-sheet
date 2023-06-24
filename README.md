## Базовые команды в Git
```
git push
git add <file_name>
git commit -m "Your message"
git push
touch <file_name>
rm <file_name>
```
## Указатели
```HEAD``` — указатель на текущий коммит или на текущую ветку (то есть, в любом случае, на коммит). Указывает на родителя коммита, который будет создан следующим.
```ORIG_HEAD``` — указатель на коммит, с которого вы только что переместили HEAD (командой git reset ..., например).
```Ветка``` (master, develop etc.) — указатель на коммит. При добавлении коммита, указатель ветки перемещается с родительского коммита на новый.
```Теги``` — простые указатели на коммиты. Не перемещаются.