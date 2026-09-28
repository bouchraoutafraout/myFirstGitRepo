user@CC:~$ git --version
git version 2.52.0
user@CC:~$ git config --global user.name "Nadushsan"
user@CC:~$ git config --global user.email "oualadi.nada@ine.inpt.ac.ma"
user@CC:~$ git config --list
user.name=Nadushsan
user.email=oualadi.nada@ine.inpt.ac.ma
user@CC:~$ mkdir myFirstGitRepo
user@CC:~$ cd myFirstGitRepo
user@CC:~/myFirstGitRepo$ git init
astuce : Utilisation de 'master' comme nom de la branche initiale. Le nom
astuce : de la branche par défaut va changer pour "main". Pour configurer
astuce : le nom de la branche initiale pour tous les nouveaux dépôts,
astuce : et supprimer cet avertissement, lancez :
astuce :
astuce : 	git config --global init.defaultBranch <nom>
astuce :
astuce : Les noms les plus utilisés à la place de 'master' sont 'main', 'trunk'
astuce : et 'development'. La branche nouvelle peut être rénommée avec :
astuce :
astuce : 	git branch -m <nom>
astuce :
astuce : Disable this message with "git config set advice.defaultBranchName false"
Dépôt Git vide initialisé dans /home/user/myFirstGitRepo/.git/
user@CC:~/myFirstGitRepo$ touch myFirstfile.c
user@CC:~/myFirstGitRepo$ ls
myFirstfile.c
user@CC:~/myFirstGitRepo$ git status
Sur la branche master

Aucun commit

Fichiers non suivis:
  (utilisez "git add <fichier>..." pour inclure dans ce qui sera validé)
	myFirstfile.c

aucune modification ajoutée à la validation mais des fichiers non suivis sont présents (utilisez "git add" pour les suivre)
user@CC:~/myFirstGitRepo$ git add myFirstFile.c
fatal : le chemin 'myFirstFile.c' ne correspond à aucun fichier
user@CC:~/myFirstGitRepo$ git add myFirstfile.c
user@CC:~/myFirstGitRepo$ git commit -m "This is my first commit!"
[master (commit racine) 4cecb70] This is my first commit!
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 myFirstfile.c
user@CC:~/myFirstGitRepo$ git checkout -b myfirst_branch
Basculement sur la nouvelle branche 'myfirst_branch'
user@CC:~/myFirstGitRepo$ git branch
  master
* myfirst_branch
user@CC:~/myFirstGitRepo$ git remote add origin https://github.com/Nadushsan/mynewrepository.git
user@CC:~/myFirstGitRepo$ git push -u origin master
Username for 'https://github.com': Nadushsan
Password for 'https://Nadushsan@github.com': 
remote: Invalid username or token. Password authentication is not supported for Git operations.
fatal : Échec d'authentification pour 'https://github.com/Nadushsan/mynewrepository.git/'
user@CC:~/myFirstGitRepo$ git push -u origin master
Username for 'https://github.com': Nadushsan
Password for 'https://Nadushsan@github.com': 
remote: Invalid username or token. Password authentication is not supported for Git operations.
fatal : Échec d'authentification pour 'https://github.com/Nadushsan/mynewrepository.git/'
user@CC:~/myFirstGitRepo$ git push -u origin master
Username for 'https://github.com': Nadushsan
Password for 'https://Nadushsan@github.com': 
remote: Invalid username or token. Password authentication is not supported for Git operations.
fatal : Échec d'authentification pour 'https://github.com/Nadushsan/mynewrepository.git/'
user@CC:~/myFirstGitRepo$ git push -u origin master
Username for 'https://github.com': Nadushsan
Password for 'https://Nadushsan@github.com': 
remote: Invalid username or token. Password authentication is not supported for Git operations.
fatal : Échec d'authentification pour 'https://github.com/Nadushsan/mynewrepository.git/'
user@CC:~/myFirstGitRepo$ git push -u origin master
Username for 'https://github.com': Nadushsan
Password for 'https://Nadushsan@github.com': 
remote: Invalid username or token. Password authentication is not supported for Git operations.
fatal : Échec d'authentification pour 'https://github.com/Nadushsan/mynewrepository.git/'
user@CC:~/myFirstGitRepo$ git push -u origin master
Username for 'https://github.com': Nadushsan
Password for 'https://Nadushsan@github.com': 
remote: Invalid username or token. Password authentication is not supported for Git operations.
fatal : Échec d'authentification pour 'https://github.com/Nadushsan/mynewrepository.git/'
user@CC:~/myFirstGitRepo$ git push -u origin master
Username for 'https://github.com': Nadushsan
Password for 'https://Nadushsan@github.com': 
remote: Invalid username or token. Password authentication is not supported for Git operations.
fatal : Échec d'authentification pour 'https://github.com/Nadushsan/mynewrepository.git/'
user@CC:~/myFirstGitRepo$ git push -u origin master
Username for 'https://github.com': Nadushsan
Password for 'https://Nadushsan@github.com': 
remote: Invalid username or token. Password authentication is not supported for Git operations.
fatal : Échec d'authentification pour 'https://github.com/Nadushsan/mynewrepository.git/'
user@CC:~/myFirstGitRepo$ git push -u origin master
Username for 'https://github.com': Nadushsan
Password for 'https://Nadushsan@github.com': 
remote: Invalid username or token. Password authentication is not supported for Git operations.
fatal : Échec d'authentification pour 'https://github.com/Nadushsan/mynewrepository.git/'
user@CC:~/myFirstGitRepo$ git push -u origin master
Username for 'https://github.com': Nadushsan
Password for 'https://Nadushsan@github.com': 
remote: Invalid username or token. Password authentication is not supported for Git operations.
fatal : Échec d'authentification pour 'https://github.com/Nadushsan/mynewrepository.git/'
user@CC:~/myFirstGitRepo$ ^[[200~git push -u origin master
bash: git: commande inconnue...
user@CC:~/myFirstGitRepo$ git push -u origin master
Username for 'https://github.com': Nadushsan
Password for 'https://Nadushsan@github.com': 
remote: Invalid username or token. Password authentication is not supported for Git operations.
fatal : Échec d'authentification pour 'https://github.com/Nadushsan/mynewrepository.git/'
user@CC:~/myFirstGitRepo$ gh auth login
bash: gh: commande inconnue...
Voulez-vous installer le paquet « gh » qui fournit la commande « gh » ? [N/y] y


 * Attente dans la file... 
 * Téléchargement de la liste des paquets.... 
Les paquets suivants doivent être installés :
 gh-2.97.0-2.el10_3.x86_64	GitHub's official command line tool
Continuer avec ces changements ? [N/y] y


 * Attente dans la file... 
 * Attente de l'authentification... 
 * Attente dans la file... 
 * Téléchargement des paquets... 
 * Requête de données... 
 * Test des changements... 
 * Installation des paquets... 

! First copy your one-time code: 2F9B-9E84
Open this URL to continue in your web browser: https://github.com/login/device
✓ Authentication complete.
✓ Logged in as Nadushsan

user@CC:~/myFirstGitRepo$ git push -u origin master
Username for 'https://github.com': Nadushsan
Password for 'https://Nadushsan@github.com': 
remote: Invalid username or token. Password authentication is not supported for Git operations.
fatal : Échec d'authentification pour 'https://github.com/Nadushsan/mynewrepository.git/'
user@CC:~/myFirstGitRepo$ ^[[200~gh auth setup-git
bash: gh: commande inconnue...
user@CC:~/myFirstGitRepo$ gh auth setup-git
user@CC:~/myFirstGitRepo$ git push -u origin master
Énumération des objets: 3, fait.
Décompte des objets: 100% (3/3), fait.
Écriture des objets: 100% (3/3), 230 octets | 230.00 Kio/s, fait.
Total 3 (delta 0), réutilisés 0 (delta 0), réutilisés du paquet 0 (depuis 0)
To https://github.com/Nadushsan/mynewrepository.git
 * [new branch]      master -> master
la branche 'master' est paramétrée pour suivre 'origin/master'.
user@CC:~/myFirstGitRepo$ git clone git@github.com:Nadushsan/myFirstGitRepo
Clonage dans 'myFirstGitRepo'...
The authenticity of host 'github.com (140.82.121.4)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
git@github.com: Permission denied (publickey).
fatal : Impossible de lire le dépôt distant.

Veuillez vérifier que vous avez les droits d'accès
et que le dépôt existe.
user@CC:~/myFirstGitRepo$ git remote -v
origin	https://github.com/Nadushsan/mynewrepository.git (fetch)
origin	https://github.com/Nadushsan/mynewrepository.git (push)
user@CC:~/myFirstGitRepo$ git clone git@github.com:Nadushsan/myFirstGitRepo.git
Clonage dans 'myFirstGitRepo'...
git@github.com: Permission denied (publickey).
fatal : Impossible de lire le dépôt distant.

Veuillez vérifier que vous avez les droits d'accès
et que le dépôt existe.
user@CC:~/myFirstGitRepo$ ls -la ~/.ssh
total 8
drwx------.  2 user user   25 28 sept. 16:08 .
drwx------. 23 user user 4096 28 sept. 16:08 ..
-rw-r--r--.  1 user user   92 28 sept. 16:08 known_hosts
user@CC:~/myFirstGitRepo$ ^[[200~ssh-keygen -t ed25519 -C "ton-email-github"
bash: ssh-keygen: commande inconnue...
user@CC:~/myFirstGitRepo$ ssh-keygen -t ed25519 -C "nadaoualadi16@gmail.com"
Generating public/private ed25519 key pair.
Enter file in which to save the key (/home/user/.ssh/id_ed25519): 
Enter passphrase for "/home/user/.ssh/id_ed25519" (empty for no passphrase): 
Enter same passphrase again: 
Your identification has been saved in /home/user/.ssh/id_ed25519
Your public key has been saved in /home/user/.ssh/id_ed25519.pub
The key fingerprint is:
SHA256:WIiwfjiDqt4dzNG4dCmlxWp2KCa7BCa7ESLVvp2gGQg nadaoualadi16@gmail.com
The key's randomart image is:
+--[ED25519 256]--+
|  .              |
|   + ...         |
|E o o .+.        |
|.= o  Oo.        |
|Oo*o+@.=S        |
|Bo+BB+*.         |
|+oo .=o          |
|ooo . .          |
|+o . .           |
+----[SHA256]-----+
user@CC:~/myFirstGitRepo$ ^[[200~cat ~/.ssh/id_ed25519.pub
bash: cat: commande inconnue...
user@CC:~/myFirstGitRepo$ cat ~/.ssh/id_ed25519.pub
ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAICZkuse7zOBQkTTxMXZUD3R4yg2pSpoE8oeZdVmY+XI6 nadaoualadi16@gmail.com
user@CC:~/myFirstGitRepo$ ssh -T git@github.com
Hi Nadushsan! You've successfully authenticated, but GitHub does not provide shell access.
user@CC:~/myFirstGitRepo$ cd
user@CC:~$ git clone git@github.com:Nadushsan/myFirstGitRepo.git
fatal : le chemin de destination 'myFirstGitRepo' existe déjà et n'est pas un répertoire vide.
user@CC:~$ git clone git@github.com:Nadushsan/myFirstGitRepo.git myFirstGitRepo-collegue
Clonage dans 'myFirstGitRepo-collegue'...
ERROR: Repository not found.
fatal : Impossible de lire le dépôt distant.

Veuillez vérifier que vous avez les droits d'accès
et que le dépôt existe.
user@CC:~$ ^[[200~git clone git@github.com:bouchraoutafraout/myFirstGitRepo.git
bash: git: commande inconnue...
user@CC:~$ git clone git@github.com:bouchraoutafraout/myFirstGitRepo.git
fatal : le chemin de destination 'myFirstGitRepo' existe déjà et n'est pas un répertoire vide.
user@CC:~$ git clone git@github.com:bouchraoutafraout/myFirstGitRepo.git myFirstGitRepo-bouchra
Clonage dans 'myFirstGitRepo-bouchra'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 6 (delta 0), pack-reused 0 (from 0)
Réception d'objets: 100% (6/6), fait.
user@CC:~$ cd myFirstGitRepo-bouchra
user@CC:~/myFirstGitRepo-bouchra$ git status
Sur la branche myfirst_branch
Votre branche est à jour avec 'origin/myfirst_branch'.

rien à valider, la copie de travail est propre
user@CC:~/myFirstGitRepo-bouchra$ ls
myFirstfile.c
user@CC:~/myFirstGitRepo-bouchra$ ^[[200~nano myFirstfile.c
bash: nano: commande inconnue...
user@CC:~/myFirstGitRepo-bouchra$ nano myFirstfile.c
user@CC:~/myFirstGitRepo-bouchra$ git status
Sur la branche myfirst_branch
Votre branche est à jour avec 'origin/myfirst_branch'.

Modifications qui ne seront pas validées :
  (utilisez "git add <fichier>..." pour mettre à jour ce qui sera validé)
  (utilisez "git restore <fichier>..." pour annuler les modifications dans le répertoire de travail)
	modifié :         myFirstfile.c

aucune modification n'a été ajoutée à la validation (utilisez "git add" ou "git commit -a")
user@CC:~/myFirstGitRepo-bouchra$ git add myFirstfile.c
user@CC:~/myFirstGitRepo-bouchra$ git status
Sur la branche myfirst_branch
Votre branche est à jour avec 'origin/myfirst_branch'.

Modifications qui seront validées :
  (utilisez "git restore --staged <fichier>..." pour désindexer)
	modifié :         myFirstfile.c

user@CC:~/myFirstGitRepo-bouchra$ git commit -m "Modification de myFirstfile.c"
[myfirst_branch 0c6323e] Modification de myFirstfile.c
 1 file changed, 1 insertion(+), 1 deletion(-)
user@CC:~/myFirstGitRepo-bouchra$ git log --oneline -2
0c6323e (HEAD -> myfirst_branch) Modification de myFirstfile.c
5e184fc (origin/myfirst_branch, origin/HEAD) Modification depuis voisinRepo
user@CC:~/myFirstGitRepo-bouchra$ git push
ERROR: Permission to bouchraoutafraout/myFirstGitRepo.git denied to Nadushsan.
fatal : Impossible de lire le dépôt distant.

Veuillez vérifier que vous avez les droits d'accès
et que le dépôt existe.
user@CC:~/myFirstGitRepo-bouchra$ git push
Énumération des objets: 5, fait.
Décompte des objets: 100% (5/5), fait.
Compression par delta en utilisant jusqu'à 20 fils d'exécution
Compression des objets: 100% (2/2), fait.
Écriture des objets: 100% (3/3), 357 octets | 357.00 Kio/s, fait.
Total 3 (delta 0), réutilisés 0 (delta 0), réutilisés du paquet 0 (depuis 0)
To github.com:bouchraoutafraout/myFirstGitRepo.git
   5e184fc..0c6323e  myfirst_branch -> myfirst_branch
user@CC:~/myFirstGitRepo-bouchra$ git pull
Déjà à jour.
user@CC:~/myFirstGitRepo-bouchra$ git log --oneline -2
0c6323e (HEAD -> myfirst_branch, origin/myfirst_branch, origin/HEAD) Modification de myFirstfile.c
5e184fc Modification depuis voisinRepo
user@CC:~/myFirstGitRepo-bouchra$ cd
user@CC:~$ touch myprogram.c
user@CC:~$ nano myprogram.c
user@CC:~$ gcc -g myprogram.c -o myprogram
user@CC:~$ ls
 bin      Documents   Modèles   myFirstGitRepo           myprogram     Public            tp1_workspace  'VirtualBox VMs'
 Bureau   Images      Musique   myFirstGitRepo-bouchra   myprogram.c   Téléchargements   Vidéos
user@CC:~$ gdb ./myprogram
GNU gdb (CentOS Stream) 17.2-4.el10
Copyright (C) 2025 Free Software Foundation, Inc.
License GPLv3+: GNU GPL version 3 or later <http://gnu.org/licenses/gpl.html>
This is free software: you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.
Type "show copying" and "show warranty" for details.
This GDB was configured as "x86_64-redhat-linux-gnu".
Type "show configuration" for configuration details.
For bug reporting instructions, please see:
<https://www.gnu.org/software/gdb/bugs/>.
Find the GDB manual and other documentation resources online at:
    <http://www.gnu.org/software/gdb/documentation/>.

For help, type "help".
Type "apropos word" to search for commands related to "word"...
Reading symbols from ./myprogram...
(gdb) b main
Breakpoint 1 at 0x40112e: file myprogram.c, line 5.
(gdb) run
Starting program: /home/user/myprogram 

This GDB supports auto-downloading debuginfo from the following URLs:
  <https://debuginfod.centos.org/>
Enable debuginfod for this session? (y or [n]) y
Debuginfod has been enabled.
To make this setting permanent, add 'set debuginfod enabled on' to .gdbinit.
Downloading 18.18 K separate debug info for system-supplied DSO at 0x7ffff7fc6000
Downloading 6.61 M separate debug info for /lib64/libc.so.6                                                                                                   
Downloading 467.55 K separate debug info for /home/user/.cache/debuginfod_client/f1c30dc33ff0976b0be944ca632125a529750888/debuginfo                           
[Thread debugging using libthread_db enabled]                                                                                                                 
Using host libthread_db library "/lib64/libthread_db.so.1".

Breakpoint 1, main () at myprogram.c:5
5	    int a = 10;
(gdb) n
6	    a = a + 1;
(gdb) p a
$1 = 10
(gdb) n
7	    printf("La valeur de a est %d \n", a);
(gdb) n
La valeur de a est 11 
8	    return 0;
(gdb) p a
$2 = 11
(gdb) n
9	}
(gdb) n
Downloading source file /usr/src/debug/glibc-2.39-141.el10.x86_64/csu/../sysdeps/nptl/libc_start_call_main.h
__libc_start_call_main (main=main@entry=0x401126 <main>, argc=argc@entry=1, argv=argv@entry=0x7fffffffdfa8) at ../sysdeps/nptl/libc_start_call_main.h:74      
74	  exit (result);
(gdb) q
A debugging session is active.

	Inferior 1 [process 15631] will be killed.

Quit anyway? (y or n) y
user@CC:~$ nano myprogram.c
user@CC:~$ gcc -g myprogram.c -o myprogram
user@CC:~$ gdb ./myprogram
GNU gdb (CentOS Stream) 17.2-4.el10
Copyright (C) 2025 Free Software Foundation, Inc.
License GPLv3+: GNU GPL version 3 or later <http://gnu.org/licenses/gpl.html>
This is free software: you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.
Type "show copying" and "show warranty" for details.
This GDB was configured as "x86_64-redhat-linux-gnu".
Type "show configuration" for configuration details.
For bug reporting instructions, please see:
<https://www.gnu.org/software/gdb/bugs/>.
Find the GDB manual and other documentation resources online at:
    <http://www.gnu.org/software/gdb/documentation/>.

For help, type "help".
Type "apropos word" to search for commands related to "word"...
Reading symbols from ./myprogram...
(gdb) b main
Breakpoint 1 at 0x40114c: file myprogram.c, line 11.
(gdb) run
Starting program: /home/user/myprogram 

This GDB supports auto-downloading debuginfo from the following URLs:
  <https://debuginfod.centos.org/>
Enable debuginfod for this session? (y or [n]) y
Debuginfod has been enabled.
To make this setting permanent, add 'set debuginfod enabled on' to .gdbinit.
[Thread debugging using libthread_db enabled]
Using host libthread_db library "/lib64/libthread_db.so.1".

Breakpoint 1, main () at myprogram.c:11
11	    int a = 10;
(gdb) n
12	    int resultat = increment(&a);
(gdb) p a
$1 = 10
(gdb) b increment
Breakpoint 2 at 0x40112e: file myprogram.c, line 5.
(gdb) c
Continuing.

Breakpoint 2, increment (a=0x7fffffffde88) at myprogram.c:5
5	    *a = *a + 1;
(gdb) a
❌️ Ambiguous command "a": actions, add-auto-load-safe-path, add-auto-load-scripts-directory, add-inferior...
(gdb) n
6	    return 42;
(gdb) p *a
$2 = 11
(gdb) finish
Run till exit from #0  increment (a=0x7fffffffde88) at myprogram.c:6
0x000000000040115f in main () at myprogram.c:12
12	    int resultat = increment(&a);
Value returned is $3 = 42
(gdb) 

