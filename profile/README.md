# Carcasonne

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
