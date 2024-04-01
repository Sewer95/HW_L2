1. **Подключения Git к проекту / инициализация нового репозитория**
    - `git init`
    - создается "скрытое хранилище" - каталог `.git/`
    - выполнять только для новых проектов
2. **Сохранение**
    - индексация файлов (добавить в очередь на сохранение)
        - `git add .`
    - фиксация (сохранение как таковое)
        - `git commit -m 'описание изменений'`
3. **Создание нового репо на GitHub**
4. **Привязка репо `LOCAL ↔ REMOTE`**
    1. `git remote add origin скопированная_ссылка`
        
        ![Screenshot from 2023-11-08 13-32-01.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/95d3eea4-bdd9-4866-805a-55b03d066b78/d1e48002-f92c-468a-854f-494c6dfe0390/Screenshot_from_2023-11-08_13-32-01.png)
        
5. **Выгрузка ветки на GitHub**
    - `git push -u origin название_ветки` (`main`, `master` и т.д.)
    - `git push -u origin main` (пример)
    - `git push` (если ветку уже выгружал)

## Стандартная последовательность команд

```bash
git add .
git commit -m 'update'
git push