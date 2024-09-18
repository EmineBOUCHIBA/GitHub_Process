# Documentation du test Git-GitHub

## **Introduction :**

### Dans un dossier :

```
git init
git remote add origin git@github.com:...
git branch -M main
```

### Après la modification d'un fichier :

```
git add filename.extension (pour un fichier)
git add filename1.extension1 filename2.extension2 filename3.extension3 (pour des fichiers en particulier du projet)
git add . (pour tous les fichiers du projet actuel)
git commit
git push origin main
```

### Rédiger un bon commit :

```
Titre du commit

Description du commit avec des informations sur l'évolution du projet
```