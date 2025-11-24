# Git Protokoll:
***
## Einmal initialisieren
`git config pull.rebase false`<br>
Nutz **merging** statt **rebase** als  methode zur Zusammenführung<p>
`pip install nbdime`<br>
`nbdime config-git --enable`<br>
Bessere kompatibilität mit jupyter notebooks (git ist für .ipynb nicht optimal)
***
## Immer
### Workflow
>**pull:** Herunterladen anderer Änderungen<br>
...<br>
**commit:** Änderungen speichern<br>
**push:** Speicherung hochladen
### Terminal Nutzung:
1. `git pull`<br>
*...Veränderungen...*
2. `git add .`(mit punkt, verwendet alle änderungen)
3. `git commit` (besser: `git commit -m "Commit message"`)
4. `git push`