# Carcasonne

# Projet de recherche sur le jeu Carcassonne

Simulation d'un ensemble de composantes connexes qui s'étend de manière dynamique et application d'un algorithme minimax de profondeur 2 afin de maximiser le nombre de points lors de la fermeture ces différentes composantes choisi par les agents.

# Téléchargement du Jeu

https://dytq.itch.io/carcassonne

# Outils de développement

## Mode Terminal 

### Clone du projet
```git clone https://github.com/Carcassonne-IA-Version-Deux-Joueurs/carcassonne```

### Compilation
```cd carcassonne```

``` make ```

### Execution
``` target/Carcassonne_lib```

## Mode Graphique
Création d'un dossier carcassonne
```mkdir carcassonne_dev```

### ÉTAPE 1: Initialisation du moteur graphique
#### Clone du moteur graphique GODOT 
``` git clone https://github.com/godotengine/godot ```

#### Sélection de la branche 3.3 version stable
``` cd godot```

``` git checkout 3.3```

#### Ajout du module carcasonne 
``` cd godot/modules ```

``` git clone https://github.com/Carcassonne-IA-Version-Deux-Joueurs/carcassonne ```

#### Compilation du moteur graphique GODOT
RTFM : https://docs.godotengine.org/en/latest/development/compiling/index.html

#### Execution du moteur graphique
dans le dossier ```/bin``` se trouve l'executable si il y a pas d'erreur

#### Rennomage du dossier godot
```mv godot godot_carcassonne```

### Étape 2: Ouverture du script graphique
Dans un autre dossier projet:
```git clone https://github.com/Carcassonne-IA-Version-Deux-Joueurs/carcassonne-graphic```
ouvrir avec l'executable godot généreré lors de la compilation le dossier

### Résultat:
Dans le dossier carcassonne_dev on a :
1. un sous dossier ```godot_carcassonne```
2. un sous dossier ```carcassonne_graphic```

# Screen Capture
![Capture d’écran du 2022-05-22 23-33-26](https://user-images.githubusercontent.com/43381918/176489950-5a8225ea-6c1c-4ef3-8a53-d09d33c222e2.png)
![Capture d’écran du 2022-05-21 19-08-30](https://user-images.githubusercontent.com/43381918/176491645-ec69e2ba-8d59-4e7a-8117-5939324e7cbe.png)
