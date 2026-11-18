# S1.01-Implementation_besoin_client
**S1.01 Implémentation d'un besoin client**


Pour mettre vos fichiers et vos modifications dans le repo, voici comment faire, dans l'ordre.

**1. Avant tout (une seule fois)**

Installez Git (git-scm.com), puis ouvrez un terminal (Git Bash sur Windows) et tapez :

```bash
git config --global user.name "Prénom Nom"
git config --global user.email "email-de-votre-compte-github"
```

Acceptez l'invitation reçue par mail pour rejoindre le repo.

**2. Récupérer le projet (une seule fois)**

```bash
git clone https://github.com/PSEUDO/sae-meteo.git
cd sae-meteo
git checkout feature/prenom-tache
```

`feature/prenom-tache` est **votre** branche, elle existe déjà. Travaillez uniquement dessus, jamais sur `main`.

**3. Envoyer votre travail sur le repo**

Une fois que vous avez modifié ou créé vos fichiers dans le dossier `sae-meteo`, tapez dans cet ordre :

```bash
git add src/votre_fichier.c
git commit -m "Description courte de ce que vous avez fait"
git push
```

La toute première fois sur votre branche, utilisez plutôt :

```bash
git push -u origin feature/prenom-tache
```

Vérifiez sur GitHub que vos fichiers apparaissent bien dans votre branche.

**4. Récupérer le travail des autres**

```bash
git checkout main
git pull
git checkout feature/prenom-tache
git merge main
```

**5. Quand votre partie est terminée**

Sur GitHub, cliquez sur **Compare & pull request**, décrivez ce que vous avez fait, puis **Create pull request**. Un autre membre relit et fusionne dans `main`.



---

Si tu veux une version encore plus courte pour un message de groupe, ou la même chose avec les captures d'écran à ajouter, dis-le-moi.
