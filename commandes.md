# Workflow

## Création d'une branche

```
git branch ma-branche					# Créer une branche
git checkout ma-branche 				# Se déplacer sur une branche
git checkout -b ma-branche  			# Créer ET se déplacer dessus (raccourci)
```

## Travail dans la branche

```
git status								# Voir les fichiers modifiés
git add .								# Ajouter tous les fichiers modifiés
git add nom-du-fichier					# Ajouter un fichier spécifique
git commit -m "Message du commit"		# Créer un commit
```

## Pousser les changements

```
git push origin ma-branche				# Envoyer sa branche sur GitHub
```

## Post merge (suppression branche)

```
git checkout main               # Changer sur main
git branch -d ma-branche				# Supprimer une branche locale
git push origin --delete ma-branche  	# Supprimer une branche distante
git pull                              # Se mettre à jour sur main
```
