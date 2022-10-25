Compte rendu TP1

1) La commande which peut prendre un ou plusieurs arguments. Pour chacun d'entre eux elle affiche sur la sortie standard (stdout) le chemin complet des exécutables qui auraient pu être saisis directement depuis le prompt Shell.
2) which -a pour avoir les options par exemple

3) ON quite le manuel avec la commande q 

Arborenscence des fichier 

1) cd /var/log
2) cd ..
3)cd -
4) cd /var
5) je n'arrive pas à acceder à cd root
6)lorsque je tape cette commande il me demande de mettre un mot de passe pour acceder au route car sans la commande sudo je n'ai pas l'autorisation d'y acceder vu que mon serveur est tp 
7)mkdir -p D1/D2/D2.1/D2.2/F2/F3
  
8) Je ne pas supprimer le fichier car t'bipu es dans ton repertoire personnel dcp tu peux pas supprimer le fichier
9) rmdir-r (supprimer un dossier vide ), le dossier est vide dans notre exemple
10) ca ne fonctionne pas 
11) on ne peut pas le supprimmer en une seule commande 

commande importante 
1) la commande date  pour afficher l'heure / commande time est utilisée pour déterminer le temps d'exécution d'une certaine commande.
2) le fichier qui commençant par un point veut dire qu'il est visible dans les documents 
3)elle se situe  dans le repertoire personnel
4)il n'y a pas d'entrée de manuel pour cette commande 
 Help allias :
tp@serveur:~$ help alias
alias: alias [-p] [name[=value] ... ]
    Define or display aliases.
    
    Without arguments, `alias' prints the list of aliases in the reusable
    form `alias NAME=VALUE' on standard output.
    
    Otherwise, an alias is defined for each NAME whose VALUE is given.
    A trailing space in VALUE causes the next word to be checked for
    alias substitution when the alias is expanded.
    
    Options:
      -p	print all defined aliases in a reusable format
    
    Exit Status:
    alias returns true unless a NAME is supplied for which no alias has been
    defined.

5) ls /bin permet d'afficher les fichier contenus
6) ls .. (Indique la fin explicite des options). 
7)pwd :Cette commande renvoie le chemin absolu (c'est-à-dire le chemin à partir du dossier racine) du dossier dans lequel on se trouve actuellement.
8)la commande echo 'bip'>plop excecuter par la commande permet de mettre son nom dans le fichier 
p@serveur:~$ echo 'bip'>plot
tp@serveur:~$ echo 'bip'>plot
tp@serveur:~$ echo 'bip'>plop
tp@serveur:~$ echo 'bip'>plop
tp@serveur:~$ ls 
D1  N1  plop  plot
tp@serveur:~$ cat plop*
bip
tp@serveur:~$ cat plop
bip
tp@serveur:~$ 
9) tp@serveur:~$ echo 'bip'>>plop
tp@serveur:~$ echo 'bip'>>plop
tp@serveur:~$ ls
D1  N1  plop  plot
tp@serveur:~$ cat bip
cat: bip: No such file or directory
tp@serveur:~$ cat plop
bip
bip
bip
10) la commande affiche toto lorque l'on fait echo'10'
11)a commande File sur Linux vous permet d’obtenir des informations sur le type de fichier.
C’est une commande utile lorsque l’on tombe sur un fichier inconnu ou que l’on a des doutes quant au type de fichier.
tp@serveur:~$ file D1
D1: directory
tp@serveur:~$ 
12)echo "hello toto !">>original
13)
14)cat /var/log/syslog
15) afficher les 5 premieres lignes du fichier
 head -n5 /var/log/syslog
16) - 
