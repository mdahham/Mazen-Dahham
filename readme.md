"OpenShift" est un cloud de programmation fonctionnant sur "redhat".
L'adress web du "OpenShift" est http://www.openshift.com

il existe 3 categories d'abonnement:
1- Online (public paas) gratuit - pour les personnes.
2- Enreprise (private paas) - pour les entreprises / un mois d'evaluation.
3- Origin (community paas) - devenir um membre de la communotee "OpenShift"
* le trem "paas" designe "platform as a service" c'est une technologie de cloud.

OpenShift nous offre un environnement compatible a une variete de language de programmation (JavaEE6, JBoss, PHP, wordpress,python...
On peut aussi utiliser la technique "push" pour inserrer/modifier le code d'apres GIT.

OpenShift aide a organiser, implemanter et structurer le code, parsuite nous donne notre temps de programmation sera plus cours et plus efficace.

Apres le login on choisie notre language de programmation desiree et on donne un nom pour notre application
si c'est la 1ere foi qu'on cree une aplication sue openshift alors nous somme besoin d'implementer notre "SSH key" sur le cloud pour qu'on puisse faire le "clone"

Selon la nature de notre application et le language de programmation on peut ajouter des moteur (gear) a notre application (SQL, Mongo, Jenkis...)

l'abonnemnet gratuit permet d'utiliser 1Gb d'espace pour chaque application

OpenShift nous genere une cle pour faire le "clone"

dans notre terminal on saisie la command "clone" suivie par la cle de openshift.

une directoire pour notre application sera cree dans "home".

Tous les fichiers necessaires pour le fonctionnement de notre application seront trouves dans cette directoire.
Ils sont configures ensembles et reliees l'un a l'autre.
pour une application web par exemple on obtient les fichires:
- stylesheet.css
- javascript.js
_ index.html

la partie <head> de "index" contient la configuration, les liens, et la descrition des fichiers "stylesheet" et "javascript".

il nous reste a implementer/ecrire notre code dans les fichires telecharges sur notre disque

via l'application "Client GIT" (sudo apt-get git install) on peut telecharger notre changements du code:
git add .
git commit (avec plusieur options pour specifier certains fichiers ou bien un seul...)
git push

de plus on peut controller notre application d'apres notre terminal (pause, restart, shutdown...) toujours via ssh.

finalement OpenShift nous donne l'option de configurer notre "domain" personnel (si on a) pour acceder a notre application

l'exercice suivant represente une page web mobile utilisant "jquery" qui a ete cree sur openshift cloud

http://webmobapp-smb214.rhcloud.com

 






