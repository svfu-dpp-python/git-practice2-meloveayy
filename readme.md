# Практика 2

1. Проверьте параметры `user.name` и `user.email` в настройках системы Git и 
   измените их при необходимости.

```
git config --global --list
```

2. Перейдите в каталог для проектов, склонируйте свой репозиторий и перейдите в 
   каталог репозитория:

```
cd <каталог проектов>
git clone <URL-репозитория>
cd <каталог репозитория>
```

2. Создайте новую ветку `feature-nod-nok`:

```
git status
git branch feature-nod-nok
git status
```

3. Измените код и выполните первый коммит:

```
git status
git add <измененные файлы>
git commit -m "<сообщение>"
```

4. Измените код и выполните второй коммит.

```
git status
git add <измененные файлы>
git commit -m "<сообщение>"
```

5. Переключитесь на ветку `main`.

```
git push -u origin feature-nod-nok
git checkout main
git status
```

6. Выполните объединение с веткой `feature-nod-nok`.

```
git merge feature-nod-nok
git status
```

7. Отправьте изменения в GitHub.

```
git push
```
