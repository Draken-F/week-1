Introduction à la POO en Python

    En Python, tout est objet : les nombres, les fonctions, les modules… chaque valeur est un objet.
    openclassrooms.com+13openclassrooms.com+13openclassrooms.com+13

    La programmation orientée objet (POO) organise le code en objets (avec attributs et méthodes) pour mieux modéliser les concepts réels.
    Wikipédia

Écrivez une classe Python

    Syntaxe :

    class NomClasse:
        def __init__(self, arg1, arg2):
            self.arg1 = arg1
            self.arg2 = arg2

    Membres de classe (variables partagées) vs membres d’instance (liés à chaque objet).
    realpython.com
    Wikipédia

    Méthodes spéciales (__init__, __str__, etc.) pour définir l’initialisation, l’affichage, les opérateurs…
    openclassrooms.com+14realpython.com+14Wikipédia+14

Créez et utilisez des objets

    Instanciation : mon_objet = MaClasse(val1, val2)

    Affichage personnalisé : en surchargeant __str__() pour obtenir une sortie lisible.
    realpython.com
    openclassrooms.com

    self : référence à l’objet courant dans les méthodes d’instance.
    Wikipédia+1realpython.com+1

Comprendre la POO

    Les concepts centraux :

        Encapsulation : regrouper données et méthodes

        Héritage : créer des sous-classes à partir de classes existantes

        Abstraction : masquer les détails d’implémentation

        Polymorphisme : objets de types différents répondant à la même interface
        openclassrooms.com+15realpython.com+15openclassrooms.com+15
        Wikipédia

Décomposez un problème orienté objet

    Analyser un problème, identifier les classes nécessaires (attributs, méthodes), structurer le code modulairement.
    ucsc-extension.edu+1datacamp.com+1

L’héritage en Python

    Syntaxe :

    class SousClasse(ClasseParente):
        def __init__(...):
            super().__init__(...)
        def methode(self):
            ...

    Possibilité de surcharger ou étendre les méthodes héritées et d’utiliser super() pour appeler la version parent.
    realpython.com
    openclassrooms.com

    Utilité de isinstance() pour tester la relation d’héritage.
    realpython.com

Modules et structuration du code

    Organiser les classes et fonctions dans des modules et fichiers séparés, favoriser la réutilisabilité et la maintenabilité du code.
    openclassrooms.com
    openclassrooms.com

Gestion des exceptions

    Apprendre à détecter et gérer les erreurs avec try, except, finally pour rendre le code plus robuste.
    openclassrooms.com

Quiz & exercices pratiques

    Chaque section est accompagnée d’un quiz pour valider la compréhension, et d’exemples ou mini-projets pour mettre en pratique (ex. créer une classe Voiture, gérer un système de bibliothèque).
    static.oc-static.com

✅ En résumé (comme votre exemple Java mais adapté à Python POO) :

Déclarer une classe et ses variables

class MaClasse:
    def __init__(self, attr1, attr2):
        self.attr1 = attr1
        self.attr2 = attr2

Créer des objets

objet = MaClasse(valeur1, valeur2)
print(objet)  # via méthode __str__()

Héritage

class Enfant(Parent):
    def __init__(self, ...):
        super().__init__(...)
    def methode_surchargée(self):
        ...

Principaux concepts

    Encapsulation → regrouper attributs et méthodes

    Inheritance (héritage) → réutilisation du code

    Abstraction → exposer une interface simple

    Polymorphisme → objets différents, interface commune

Modules, structuration, exceptions, quiz & exercices

    Découpage du code en fichiers/modules

    Gestion des erreurs avec try/except

    Apprentissage par exercices et quiz interactifs

