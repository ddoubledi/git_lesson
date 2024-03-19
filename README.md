# git_lesson
Git lesson overview


# create repository
```sh
git init
```

# Статус
```sh
git status
```

# Додавання файлу(файлів)
```sh
git add {file_name}
```

# Коміт
```sh
git commit --m "Commit message"
```

# Коміт із додаванням всіх файлів
```sh
git add .
git commit -m "Commit message"
```

```sh
git commit -am "Commit message"
```

# git log
```shell
git log
```

# git remote
```shell
git remote add origin git@github.com:ddoubledi/git_lesson.git
```

# git push
```shell
git push origin main
```

# Створення нової гілки
```shell
git checkout -b "new_branch"
```

# Завантажити зміни з гіта(pull)
```shell
git pull origin main
```


# Сквош двох комітів в один
```shell
git rebase -i HEAD~2
```


# Hard push 
```shell
git push origin squash_example -f
```
