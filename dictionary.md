1. **git reset HEAD filename** - удалит уже добавленный в index файл filename
2. **git revert commit-SHA** - удалит комминт с указанным SHA из репозитория (на самом деле откатит изменения и создаст новый коммит, который нужно будет запушить)
3. **git add --force filename** - добавить файл filename в index даже если он исключен (команда 1 или .gitignore)