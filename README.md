[Git parancsok vizualizációja](https://dev.to/lydiahallie/cs-visualized-useful-git-commands-37p1)

# Alapok

`git commit`

View-ban lévő változtatások commit-álása.

`git branch <branch név>`

Új branch létrehozása, ami az aktuális commit-ra mutat. A pointer nem vált automatikusan az új branch-re.

`git checkout <branch név>`

A pointer mozgatása az új branch-re.

`git checkout -b <branch név>`

Új branch létrehozása és a pointer mozgatása. Ekvivalens az előző 2 parancs lefuttatásával.

`git merge <branch név>`

Megadott branch merge-ölése arra a branch-re, amire a pointer mutat.

`git rebase <branch név>`

A pointer által kijelölt branch összes commit-jának másolása a megadott branch-re.