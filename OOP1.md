Déclarer les variables

    Syntaxe :

    type nomVariable = valeur;
    final type CONSTANTE = valeur;

    Types primitifs courants : int, long, float, double, boolean, char, byte, short
    openclassrooms.com+15Wikipédia+15Scribd+15

    Types objets (wrappers) : Integer, Double, etc., permettent la nullabilité
    Wikipédia

✳️ Fonctions (méthodes) Java

    Structure typique :

    public static void nomMethode(Type param) {
        // code
    }

    public/private, static, void ou type de retour, nom, paramètres
    Wikipédia
    Studocu

📦 Portée des variables

    Locale : définie à l’intérieur d’un bloc {}

    Global (de classe) : variables de classe (static) vs d’instance

    Constantes : déclarées avec final

🔁 Types de boucles

    for : traditionnel ou for-each (Java 5+)

for (int i = 0; i < n; i++) { … }
for (Type item : collection) { … }

while :

while (condition) { … }

do-while :

    do { … } while (condition);

    openclassrooms.com
    Scribd+15Wikipédia+15openclassrooms.com+15

🔀 Conditions

    if / else if / else :

if (cond1) { … }
else if (cond2) { … }
else { … }

switch (depuis Java 7 supporte String et enum) :

    switch (variable) {
      case valeur1: … break;
      case valeur2: … break;
      default: … break;
    }

    Wikipédia
    Studocu

🏛️ Classe & Objet

    Déclaration d'une classe :

class Book {
    // attributs et méthodes
}

Création d’objet :

    Book livre = new Book();

🚀 Héritage & interfaces

    Héritage simple (extends) :

    class SousClasse extends SuperClasse { … }

    Interfaces et interface fonctionnelles (Java 8+) avec implements

    On peut hériter de méthodes ou variables final mais ne pas les modifier
    openclassrooms.com+4Wikipédia+4academia.edu+4

🧮 Tableaux (arrays)

    Déclaration :

int[] nombres = new int[5];
int autres[] = {1,2,3};

Accès & modification :

    System.out.println(nombres[0]);
    nombres[1] = 100;
    ``` :contentReference[oaicite:27]{index=27}  

📚 Collections (Listes et Dictionnaires)

    Liste dynamique :

List<Type> nomListe = new ArrayList<>();
nomListe.add(objet);
nomListe.get(index);
nomListe.set(index, objet);
nomListe.remove(index);

Dictionnaire :

    Map<Cle, Valeur> map = new HashMap<>();
    map.put(cle, valeur);
    map.remove(cle);
    ``` :contentReference[oaicite:28]{index=28}  

⚠️ Gestion des exceptions

    Syntaxe :

    try {
        // code pouvant lever une exception
    } catch (ExceptionType e) {
        // gestion
      } finally {
        // toujours exécuté
    }

    Rend le code plus robuste en traitant les erreurs anticipées
    openclassrooms.com
    Studocu

🧬 Généricité, tests et E/S

    Génériques : listes typées sécurisées (ex. List<String>)
    openclassrooms.com+11Studocu+11Wikipédia+11

    Entrées/Sorties : utiliser des flux (InputStream, Reader, Writer, etc.) pour lire/écrire des données
    Studocu

    Tests automatisés avec JUnit 5 pour valider votre code de manière fiable