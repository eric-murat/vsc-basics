# Visual Studio Code - les bases
https://code.visualstudio.com/

# Process pour sauver son travail sur Git
1. Depuis le menu latéral `Contrôle de code source` : cliquer sur "Mettre en attente les modifications" (bouton `+`)
2. Cliquer sur "Activer" (bouton "✔️") pour commiter les changements indexés. Saisir le message du commit.
3. Cliquer sur le bouton "Synchroniser les modifications"
Note : si message d'erreur "Permission denied (publickey)", voir §ce paragraphe

# Résolution de l'erreur Permission denied (publickey) lors du `git push`
Source : https://www.youtube.com/watch?v=UrRceV11B8Y
1. Depuis GitHub.com, sur son repository, sélectionner HTTPS au lieu de SSH
2. Depuis le terminal de VS Code, saisir : 
```
git remote rm origin
git remote add origin https://github.com/eric-murat/bs-ex01.git
```
3. Recommencer le `git push`. A noter : une fenêtre d'authentification risque d'apparaître la 1ère fois.

