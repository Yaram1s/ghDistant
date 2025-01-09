Hook Git : pre-commit

Description :
Ce hook `pre-commit` demande si l'utilisateur souhaite sauvegarder des informations
sur le commit dans un fichier `suivi/commitInfo.txt`.

Installation :
1. Copiez le fichier `pre-commit` dans le dossier des hooks de Git :
   cp hooks/pre-commit .git/hooks/pre-commit

2. Rendez le fichier exécutable :
   chmod +x .git/hooks/pre-commit

Le hook sera exécuté automatiquement à chaque commit.
