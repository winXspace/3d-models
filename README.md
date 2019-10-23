# 3d-models
3D модели, не относящиеся на прямую к роботу(учебные, творчество и т.п....)

Памятка по работе с github.
Предполагается что git установлен и [настроен](https://git-scm.com/book/ru/v2/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%9F%D0%B5%D1%80%D0%B2%D0%BE%D0%BD%D0%B0%D1%87%D0%B0%D0%BB%D1%8C%D0%BD%D0%B0%D1%8F-%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D0%B0-Git). Как и [github ssh](https://help.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh).

1. Клонируем репозиторий:
Зелёная кнопка на главной странеце репозитория -> копировать в буфер обмена строку-адрес (например git@github.com:winXspace/3d-models.git).
Далее у себя на машине в командной строке git:
``` bash
cd winXspace
git clone git@github.com:winXspace/3d-models.git
cd 3d-models
```
2. Сохраняем модель внутри папки репозитория. Например файл my-model.dwg
3. Можно создать свой бренч и переключится на него(чтобы не коммитить в мастер):
```bash
git branch andew-models
git checkout andrew-models
```
4. Добавляем файлы для git:
```bash
git add *
```
5. Коммитим с комментарием:
```bash
git commit -am "Моя новая модель держалки серво для робота"
```
6. Пушим на сервер чтобы все увидели нашу модель:
```bash
git push origin andrew-models
```
