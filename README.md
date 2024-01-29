# TMDB

Данное приложение позволяет скачать огромную базу данных с сайта https://www.themoviedb.org, и осуществлять поиск по ключевым словам!

## Как работает

Программа имеет 4 основных скрипта

### Требования к использованию

Для работы со скриптами требуется завсети ключ API [здесь](https://www.themoviedb.org/documentation/api).

### hello_api_TMDB.py
С помощью этого скрипта, вы можете проверить свой API ключ и установить пробное подключение.
Результатом будет бюджет фильма.
>Пример вывода функции hello_api_TMDB.py.
+ ![Screenshot_1](https://github.com/dendevkoz/TMDB/blob/main/TMDB_screenshots/hello_api_TMDB.png)

### make_own_db.py

Скачивает базу данных фильмов с сайта https://api.themoviedb.org и сохраняет её в виде файла JSON.
>Пример вывода функции make_own_db.py.
+ ![Screenshot_2](https://github.com/dendevkoz/TMDB/blob/main/TMDB_screenshots/make_own_db.png)
 
### search_in_db.py

Позволяет найти все фильмы, отсортировать и вывести, где в названии встречаются запрошенное ключевое слово.
>Пример вывода функции search_in_db.py.
+ ![Screenshot_2](https://github.com/dendevkoz/TMDB/blob/main/TMDB_screenshots/search_in_db.png)

### find_similar.py
На вход принимает название фильма. Результатом является несколько фильмов которые максимально подходят по параметрам.
>Пример вывода функции find_similar.py.
+ ![Screenshot_2](https://github.com/dendevkoz/TMDB/blob/main/TMDB_screenshots/find_similar.png)



## Осталные скрипты являются вспомогательными 


### own_db_helpers.py

Содержит функцию благодаря которй возвращает данные по фильмам в формате .json из нашего файла, но ничего не выводит.

### tmdb_helpers.py

Содержит общие функции благодаря которым получает информацию по фильмам через запросы к API, но ничего не выводит.


## Для использования необходимо 

```
[Python3](https://www.python.org/downloads/) должен быть уже установлен.
```
Затем используйте `pip` для установки зависимостей:
```
pip install -r requirements.txt
