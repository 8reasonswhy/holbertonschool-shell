Script-1 pwd = print working directory 
il nous affiche le chemain de notre dossier de travail

Script-2 ls = liste the files of the urrent working directory 
ca affiche tout les fichier et les doc contenue dans notre dossier actuel

Script-3 cd ~ = Ca nou pemet de nous diriger vers homme
le ~ repr�sente le home de chaque user on va dire que c'est une variable globale qui représente le chemain hom

Scripte-4 ls -l = ca nou permet d'afficher les fichier de notre repertoir actuel mais en long format grace  -l

Scripte-5 ls -la = alors comme la question d'apres ls avec -l affiche tous les fichier en detail et en ajoutant la -a ca affiche les fichier cacher

Scripte-6 ls -ls --numeric-uid-gid = alors j'ai rien compris l'utilité mais il disent ca affiche les choses avec leurs id

Scripte-7 mkdir = "Ennft la je sais bien mkdir mais j'ai appri la difference entre /tmp et ./tmp alors / ca veut dire le chemain absolue mais ./ ca veut dire le chemain relatif c'est adire quand on met ./ 
notre point de départ est notre repertoire actuel de travail 

Scripte-8 mv = " on d�place un dossier ou un fichier grace a la commande mv

Scripte-9 rm= "Pour supprimer un fichier on fait rm tout court mais si on veut supprimer un dossier on fait rmdir et si le dossier et pein faut utiliser rm -r"

Scripte 10 rm -r = "Alors la  pour supprimer un fichier on utilise rmdir sauf que si le fichier et plein ca refuse de le supprimer c'est pour cela il est préferable d'utiliser rm - r 
et si on veut forcer un peu plus on utilise rm -rf -f pour forcer les trucs mais faut faire attention car ca commande et irreverssible et demande pas de confirmation quand y'a le -f"

Scripte11 cd .. = "Pour revenir au arrier genre a la directrory just precedente en execute la commande cd .."

Scripte file = " on utilise la commande file pour nous dire le type de fichier "

Script 12  = " alors pour afficher les files avec les detail en utilise ls -l pour afficher les fichier cacher on a besoin de -a donc pour afficher les fichier cacher en long format on utilise ls -la 
alors ce que j'ai appris c'est que . reffer to the wd alors que .. reffer to the parrent et on peut concatenez en une seul ligne tous ce qu'on veut affichier ls -la . .. /boot "

Scripte-13 = " Pour créer un link symbolic on utilise la commande ln -s  //// -s ce qui montre un link SYMBOLIC au contraine du hard link "

Scripte-14 = " find . la commande fait la recherche . c'est a dire dans le rep courant 
		-maxdepth 1 c'est a dire ne cherche pas des ficher dans les dossier contenue dans le rep courant 
		-exec c'est a dire le code qui doit etre executer apres la que la recherche a été faites 
		test pour faire le test 
		-nt = newer than 
		-o pour dire tester la second test si le premir a echouer
		et on separe toucjours les comadne par un \;  
