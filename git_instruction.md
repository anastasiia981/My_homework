## Работа с удаленным репозиторием
1. Чтобы работать в удаленном репозитории с локального, применим: 
```sh
git clone (ссылка на репозиторий)
```
2. Возврат в предыдущую папку:
```sh
cd ..
```
3. Переместить данные с локального репозитория в удаленный:
```sh
git push
```
4. Переместить данные с удаленного репозитория в локальный:
```sh
git pull
```
5. Создание новой папки из терминала:
```sh
mkdir (имя папки)
```
6. Переименовать ветку:
```sh
git branch -m (имя ветки)
```
7. Получить информацию и ссылки по нашему удаленному репозиторию:
```sh
git remote show или git remote show origin
```
8. Получить ссылки на Push и Pull:
```sh
git remote -v
```
9. Удаление ветки из удаленного репозитория, прямо в терминале:
```sh
git push origin --delete (имя ветки)
```
10. При возникновении кофликта:
```sh
git pull --rebase
```

