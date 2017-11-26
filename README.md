# Git tutorial

### Qu'est-ce que git

- principe
- github / bitbucket / serveur
- ligne de commande / desktop gui
- local / remote
- historique
- pull request

### Installation de git

- creer un compte
- installer git sur la machine
- lier le compte à la machine : `git config --global --edit`
- ou lier le user name `git config --global user.name "John Doe"`
- et lier le user email `git config --global user.email johndoe@example.com`
- [Why is Git always asking for my password?](https://help.github.com/articles/why-is-git-always-asking-for-my-password/)
- aide : `git help <verbe>`

### Initialiser un repository

- créer le repo : `git init` dans le dossier ou [Via github](https://github.com/new)
- commit initial : `git add file`, `git commit -m "message"`, `git push`

### Gérer un repository / commandes

- `pull` / `commit` / `push`
- `fetch` / `add` / `clone` / `status`
- `git commit --amend`
- `branch` / `checkout` / `checkout -- file` / `add .`
- `log`
- `diff`
- `merge`
- `reflog`
- `reset #{HEAD1}` / `reset --hard origin/master`
- `rebase`
- `rebase -i` (interactif)

---

### Liens

- [Github](https://github.com/) / [Bitbucket](https://bitbucket.org/)
- [Documentation en français](https://git-scm.com/book/fr/v2)
- [git the simple guide](http://rogerdudler.github.io/git-guide/)
- [Atlassian documentation](https://www.atlassian.com/git/tutorials)
- [Bien utiliser git merge et rebase](https://delicious-insights.com/fr/articles/bien-utiliser-git-merge-et-rebase/)
