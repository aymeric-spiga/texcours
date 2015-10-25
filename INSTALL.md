## Important

Cette suite de notes de cours utilise le package perso tex
https://github.com/aymeric-spiga/tex
Récupérer les sources en local dans un dossier /mon-home/ou-je-veux/tex

Ajouter le chemin à la variable environnement TEXINPUTS

	tex=/mon-home/ou-je-veux/tex/
	TEXINPUTS=$TEXINPUTS:$tex/latex/
	export TEXINPUTS

Ajouter également les dossiers de texcours pour une utilisation aisée

	texcours=/mon-home/ou-je-veux-ailleurs-ou-non/texcours
	TEXINPUTS=$TEXINPUTS:$texcours/archives
	TEXINPUTS=$TEXINPUTS:$texcours/fiches
        TEXINPUTS=$TEXINPUTS:$texcours/pkg
	export TEXINPUTS

## Template

Voir exemple template.tex dans cours/	
