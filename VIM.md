# Normal mode keys
## Навигация
h      - left
j      - down
k      - up
l      - right

gg     - на начало файла
G      - на конец файла

0      - в начало строка
$      - в конец строки

w      - слово вперёд
b      - слово назад
e      - до конца слова

## Сменить режим
v      - режим выделения
V      - режим выделения по строкам

i      - режим редактирования (insert) 
a      - режим редактирования (apped)
o      - line down and enter insert mode
O      - line up and enter insert mode

## Разное
u      - отменить действие (undo)
Ctrl+r - отменить в другую сторону (redo)

y      - скопировать (yank, copy)
p      - втравить (past)
d      - удалить и скпировать (delete)

Есть кнопки которые ожидают ввода другой кнопки
тоесть такие сочетания как 
yw - скопирует до начала следующего слова
db - удалит до начала слова
yy - копиррует всю строку
сответсвенно 
dd - удаляет всю строку

# Режим выделения
o      - revers cursor posiotion
d      - delete and yank selected
y      - yank selected

# Команды
:q     - exit
:q!    - force exit
:w     - save file
:w!    - force save file
:wq    - save and exit

# Специально для руслана
ggVG - выделить всё
