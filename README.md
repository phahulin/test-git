1. в интерфейсе github.com создаем новый репозиторий, не забываем выбрать лицензию
2. добавляем свои ssh ключи в разеделе настроек аккаунта
3. клонируем репозиторий: `git clone git@github.com:phahulin/test-git.git`
4. создаем README: `touch README.md` и простой скрипт на питоне `echo 'print("Hello, world!")' > script.py`
5. добавляем файлы в git и пушим `git add .`, `git commit -m "Initial commit"`, `git push origin main`
6. создаем новую ветку `git checkout -b test_merges`, вносим изменения в `script.py` и пушим их в удаленный репозиторий
7. открываем новый merge-request https://github.com/phahulin/test-git/pull/1
8. описываем все шаги в этом README и пушим их