## Node.js

[Node.js](https://nodejs.org/en/) est un programme d’exécution JavaScript qui permet d’exécuter du code JavaScript dans le terminal. On va l’installer avec [nvm](https://github.com/nvm-sh/nvm), un gestionnaire de versions pour Node.js.

Exécute la commande suivante dans ton terminal :

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.0/install.sh | zsh
```

Redémarre ton terminal et exécute la commande suivante :

```bash
nvm -v
```

Tu devrais voir apparaître une version. Sinon, demande au prof.

On va maintenant installer node :

```bash
nvm install 14.15
```

Une fois l’installation terminée, exécute :

```bash
node -v
```

:heavy_check_mark: Si tu vois apparaître `v14.15`, l’installation a réussi :+1:

:x: Sinon, **demande au prof**