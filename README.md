# Bienvenue sur Oh My Food 


## Qu’est-ce que c’est ? 

Oh my food est un site web présentant quatres menus de grands-chefs français. J'ai réalisé ce site web du début à la fin, entièrement en HTML/CSS, durant l’été 2020, dans le cadre de ma formation de développeur web chez Openclassrooms (OC).

Vous pouvez voir le résultat ici : https://flora-pvt.github.io/p3-ohmyfood/ 

Ce projet maintenant fini a été créé à partir de visuels fournies par OC.

    
## Comment le modifie-t-on ?

Si vous souhaitez utiliser ce projet et y apporter des modifications il est nécessaire d'installer le préprocesseur Sass.
    
### Pourquoi Sass ?

Sass permet d'alléger notre CSS et le rend plus facile à maintenir.
Ce préprocesseur permet d'utiliser des fonctionnalités qui n'existent pas encore dans CSS, comme les variables, l'imbrication, les mixins, l'héritage et d'autres bonus astucieux qui rendent l'écriture CSS plus simple à maintenir.
Il permet de créer plusieurs fichiers .sass ou .scss, de les organiser pour savoir rapidement lequel modifier si besoin d'une correction ou d'un ajout, et de les compiler automatiquement en un fichier .css allégé utilisé par notre site web. 

### Comment utiliser Sass ?

Pour installer et apprendre Sass consultez le site web de Sass qui vous guidera : https://sass-lang.com/ 

Une fois que vous avez installé Sass, vous pouvez exécuter Sass pour compiler les fichiers .scss en un fichier .css en écrivant dans la ligne de commande de votre terminal :
`npm run sass`

Tant que vous n’interrompez pas le processus, soit en tapant Ctrl+C dans le terminal, soit en cliquant sur la corbeille, le script attendra et sera à l'affût de tout changement à compiler.
Si tout a fonctionné comme prévu, la ligne de commande va repérer le changement puis nous indiquera qu’elle a recompilé le CSS en vert.

Une fois compilés les fichiers en un fichier .css vous pouvez ajouter les préfix nécessaires automatiquement pour tous les navigateurs en écrivant dans la ligne de commande de votre terminal :
`npm run prefix`