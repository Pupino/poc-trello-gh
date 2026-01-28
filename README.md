# poc-trello-gh

Trello Project Traceability with GH

Steps to connect Trello with Github:

1. Create Repository on GitHub
2. Create a folder on you local computer to centralize all repositories that you're going to have, ex: 'Repositories'
3. Open vscode terminal and navigates to that previous folder, to clone in there the created repo
4. Go to Github Copia la URL: Ve a tu repositorio en GitHub, haz clic en el botón verde que dice "<> Code" y copia la URL que aparece ahí (asegúrate de que esté seleccionada la pestaña HTTPS, que es la más sencilla para empezar).
5. Run: git clone https://github.com/<user>/<repository-name>.git
6. Navigates tu the folder on your terminal: cd <repository-name>
7. add some changes and commit adding the related ticket url https://trello.com/c/289M9EY9 to the comment

git add README.md
git commit -m "docs: initial setup of Project Ref: https://trello.com/c/289M9EY9"
git push origin main

Standars rules

feat:
fix:
docs:
style:
refactor:
chore:
