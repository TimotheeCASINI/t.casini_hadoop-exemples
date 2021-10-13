# Timothée CASINI - BigData Frameworks - DS6
TP4 - Yarn&MapReduce 2 - Git Hub Respository

### Initialisation du dépôt **GitHub** :

- On commence par créer un respository (public) et on le nomme : 
  * `t.casini_hadoop-exemples`

<br>

- Ensuite on clone le dépôt contenant le dossier *hadoop-exemples-mapreduce* dans l'environnement **Hadoop** :
  * `git clone https://github.com/makayel/hadoop-examples-mapreduce.git`

![Dépôt hadoop-exemples-mapreduce](imgs/img1.jpg)

<br>

- On clone maintenant notre **dépôt GitHub personnel** dans le dossier *MyGitHub* :
  * `git clone https://github.com/Gratouille123/t.casini_hadoop-exemples.git ./MyGitHub`

![Dépôt personnel](imgs/img2.jpg)

<br>

- On copie le dosssier *hadoop-exemples-mapreduce* dans le dosssier *MyGitHub* afin de pouvoir le transferer au dépôt **GitHub** :
  * `cp -R hadoop-examples-mapreduce ./MyGitHub`

![Copie du dossier vers notre git](imgs/img3.jpg)
![Vérification de la copie](imgs/img4.jpg)

<br>

- On ajoute le dossier *hadoop-exemples-mapreduce* au dépôt **GitHub** puis on valide l'ajout :
  * `git add -f hadoop-examples-mapreduce/\*`
  * `git commit -m "Insertion du dossier hadoop-exemples-mapreduce"`

![Ajout du dossier dand le dépôt](imgs/img5.jpg)

<br>

- On génère un **token d'accès** depuis le **GitHub** afin de pouvoir **push** les donner vers le dépôt personnel :
  * `TOKEN = Ghp_wSKqEiOAfwMres8lmiRk40qiASb8ID3hl4F2`
  * `git push` => Password for 'https://Gratouille123@github.com': [PUT TOKEN HERE]

![Insertion du dossier dans le Git](imgs/img6.jpg)


<br>

Ainsi, le dossier *hadoop-exemples-mapreduce* a été chargé dans le dépôt personnel **GitHub** nommé : `t.casini_hadoop-exemples`

Il ne reste plus qu'a cloner le dépôt depuis un terminal (dans le référentiel souhaité) : 

`git clone https://github.com/Gratouille123/t.casini_hadoop-exemples.git`
