![image](https://user-images.githubusercontent.com/52743561/170463016-04c6e717-1c89-47db-a915-fcb2052566b6.png)

> Короче, я сидел и думал: почему нет нормальных синонимайзеров текста?
> 
> Они все неграмотные, ну вот я сделал такую простую штуку
> 
Он умеет при помощи гугл переводчика гонять текст между языками. При этом переставляются члены предложений, слова заменяются синонимами и тд.

# ♿Как ставить
⚠Модули
```bat
pip install colorama
pip install googletrans==3.1.0a0
pip install Levenshtein
```
# Демонстрация
🍎Оригинал
```
Собачка легла на спину, подняла лапки и стала махать хвостиком.
Лев тронул её лапой и перевернул.
Собачка вскочила и стала перед львом на задние лапки.
Лев смотрел на собачку, поворачивал голову со стороны на сторону и не трогал её.
```
🍏Синтет
```
Собака легла на спину, подняла лапы и стала вилять хвостом.
Лев коснулся ее лап и перевернул ее.
Собака вскочила и встала перед львом на задние лапы.
Лев посмотрел на собаку, покачал головой из стороны в сторону и не прикоснулся к ней.
```
>Получилось даже более современно что-ли...
