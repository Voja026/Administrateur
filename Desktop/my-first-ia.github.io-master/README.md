 # Initiation JS
 L'objectif de cet atelier est de se familiariser avec le langage Java Script en vue de manipuler simplement le DOM.
 Il consiste à comprendre comment est construite la page suivante : https://joz84.github.io/my-first-ia.github.io/
 Tout le code est mis à disposition et notemment le code JS situé dans le fichier https://github.com/Joz84/my-first-ia.github.io/blob/master/js/application.js.

 ## Etape 0 : Créer un programme d'IA très basic en python :
 Remarque vous pouvez écrire le programe dans le fichier code.py et l'executer en tapant la commande suivante dans votre terminal :
```
  python code.py
```

  - Créer un programme qui pause une question à l'utilisateur et en fonction de la réponse revoie un message prédéfini. Le programme doit exactement inclure:
  - Au moins une déclaration de variable
  - Un tableau (array)
  - Une itération et/ou une condition (if ...)

  Il devra être de cette forme là :
  - On pause une question et on stock la réponse de l'utilisateur dans une variable "answer".
  - On definit une methode "create_message" qui prend pour parametre "answer"
  - En fonction de cette answer la methode trouve et retourn le message adapté
  - Affiche la réponse

  Autrement dit il doit être de la forme suivante :
```
  answer = input("question ?")

  def create_message(answer):
    # votre algorithme
    return message

  print(message)
 ```

 ## Etape 1 : Convertir ce programme en un programme JS :
  Remarque vous pouvez écrire le programe js dans le fichier code.js et l'executer en tapant la commande suivante dans votre terminal :
```
  node code.js
```
 Le programme doit faire exactement la même chose que le programme python. A vous de trouver la correspondance.

 ## Etape 2 : Quizz :
Remarque: Le code JS n'est pas écrit avec les nouvelles normes ES6. Une partie des questions consistent à voir la différence entre les deux syntaxe.
  - A quoi sert console.log ?
  - A quoi sert var ?
  - Quelle est la différence avec const et let ?
  - Comment définir une fonction en JS ?
  - Quelle est la nouvelle syntaxe d'une fonction en ES6 ?
  - A quoi sert "document" ?
  - Quelle est la différence avec "window" ?
  - A quoi sert querySelector ?
  - Quelle est la différence avec getElementById et querySelectorAll ?
  - A quoi sert addEventListener ?
  - Citer d'autre events pouvant être écoutés ?
  - A quoi sert innerText ?
  - Quel est la différence avec innerHTML et InsertAdjacentHTML ?
  - Qu'est que la concatenation ?
  - Quelle est la différence avec l'interpolation ?
  - Citer la methode qui permet de faire une itération ( elle n'est pas dans le programme )

 ## Etape 3 : Modification du programme :

  - Remplacer les "var" par les bons mots
  - Ecrire la fonction avec la nouvelle syntaxe
  - Utiliser une autre methode que querySelector
  - Remplacer la concatenation par une interpolation
  - Utiliser une autre methode que innerText

 ## Etape 4 : Utiliser ce dossier comme exemple pour créer votre page

  - Modifier les noms des id et des varaibles pour qu'ils correspondent à votre programme (s'assurer que ca marche toujours :) )
  - Convertir votre programme python en programme JS (Il devrait être dans la fonction "createMessage")
  - Faire un peut de CSS pour rendre ca Jolie

 ## Etape 5 : Mettre en ligne sur GitHhub

  - S'assurer que le nom du dossier finisse par ".github.io" (ca vous simplifiera la vie pour la suite :) )
  - Initialiser git sur ce projet
  - Mettre ce projet sur github
  - Mettre ce projet en ligne accessible à tous

