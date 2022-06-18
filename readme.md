# Explication des dépots de code présents sur mon compte :

Je me nomme Gaspard COURCHINOUX, je suis un programmeur des systèmes bas niveaux. 

J'ai écrit une architecture s'appelant Gaspard. 
j'ai effectué le port logiciel de cette architecture sur gcc , binutils et bientot le noyau linux ! 



# binutils : 



pour binutils il faut écrire le support des branchements et des sauts (B. et Jsr et jump) 
Il faut rajouter le support dans gas et libopcode

# gcc 
base de gcc 10. 

pour gcc normalement la backend génére un code correct. Il faudrait faire des tests et rajouter les derniers GPR ET FPR qui ne sont pas implémentés. 



# linux 

base de linux 5.10 lts. 

Je suis en train de comprendre comme cela fonctionne mais visiblement il faudra d'abord que je patche binutils. 

