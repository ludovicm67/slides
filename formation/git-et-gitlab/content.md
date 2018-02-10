# Formation `git` et GitLab

## Présentation de `git`

### Utilité

### Installation

Sur la majorité des systèmes, `git` n'est pas installé par défaut.
Mais cela est une opération très simple et rapide.

Nous allons voir comment l'installer, que vous soyez sur une distribution linux
ou bien sur Windows.

#### Sur linux

Sur linux, l'installation se fait très rapidement.

Lancez simplement la commande suivante :

```bash
$ sudo apt install git
```

#### Sur Windows

Ouvrez votre moteur de recherche favoris, et cherchez simplement les termes
`git windows`, vous devrez tomber sur un lien : https://git-scm.com/downloads .


#### Configuration

La commande `git` est donc désormais bien installée.

Il ne reste plus qu'à le configurer rapidement.
En effet, pour le moment `git` ne connaît pas l'identité qui devra être
utilisée pour les différents commits.

Il faut donc lui dire quelle adresse mail et quel pseudo utiliser, et cela se
fait de la manière suivante :

```bash
$ git config --global user.name "John Doe"
$ git config --global user.email "john.doe@example.com"
```

Pour ceux qui souhaitent configurer `git` pour utiliser un éditeur
particulier (`vim`, `emacs`, ...) :

```bash
$ git config --global core.editor vim
```

Le choix de l'éditeur est facultatif; en général par défaut on a `nano`.
L'éditeur est utilisé lorsque `git` a besoin qu'on lui renseigne un message,
par exemple lors des commits, des merges, etc... mais on verra ça plus en
détail plus tard.

### Les commandes de base

#### `git init`

Permet d'initialiser un nouveau dépôt.

Par exemple vous avez un projet dans un répertoire (qu'il soit vide ou non),
et vous souhaitez tout d'un coup le versionner ?
Placez vous dans ce répertoire et lancez un coup de `git init` !

Et voilà, vous avez un dépôt `git`; facile, non ? :-)


#### `git clone [url]`

#### `git status`

#### `git add [fichier1 fichier2...]`

#### `git add -A`

#### `git commit -m "ce que j'ai fait"`

#### `git push`

#### `git pull`

### Les branches

### Gérer les conflits

### Les tags

## GitLab

### Présentation

### Configuration

Maintenant que vous avez fait connaissance de votre nouvel ami, il aimerait
également vous connaître à son tour.

Place à un peu de configuration !
(promis, ce ne sera pas long)

#### Ajouter sa clé SSH

#### Ajouter une adresse mail

#### Les groupes

#### Mise en pratique !

