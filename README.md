# js_object

// Objet String

1 --> includes(1para)            - déterminer si une chaîne de caractères est contenue (incluse) dans une autre.

2 --> startWhit(1para)           - déterminer si une chaîne de caractères commence par une certaine sous chaîne.

3 --> endWith(1para)             - déterminer si une chaîne de caractères se termine par une certaine sous chaîne.

4 --> substring(1para/2option)   - retourne un morceau de la chaîne courante à partir d’un indice de départ.

5 --> substr(1para/2option)      - n'est plus recommandée

6 --> indexOf(1para/2option)     - trouver la position de la première occurrence d’un caractère ou d’une chaîne
de caractères dans une chaîne de caractères de base.

7 --> lastIndexOf(1para/2option) - renvoie l’index de la dernière occurrence ou -1 si rien n’a été trouvée dans la chaîne.

8 --> slice(1para/2option)       - extrait une section d’une chaîne de caractères et la retourne comme une nouvelle chaîne de caractères.
La chaîne de caractères de départ n’est pas modifiée.

9 --> replace(1para/2para)       - permet de rechercher une chaîne ( ou caractère ) dans une chaîne de caractères et de la remplacer par une autre.

10 --> toLowerCase(/)            - retourne une chaîne de caractères en minuscules.

11 --> toUpperCase(/)            - retourne une chaîne de caractères en majuscules.

12 --> trim(/)                   - supprime les espaces ou les « blancs » en début et en fin de chaîne

13 --> split(séparateur" ")      - diviser une chaîne de caractères à partir d'un séparateur pour fournir un tableau de sous-chaînes.


// Objet Number

1 --> isInteger(type number)  - déterminer si une valeur est un entier valide.

2 --> isNaN(1para)            - déterminer si la valeur passée en argument est la valeur NaN.

3 --> parseFloat(1para)       - convertir une chaîne de caractères en un nombre décimal.

4 --> parseInt(1para/2option) - convertir une chaîne de caractères en un entier ( Number ).

5 --> toFixed(1para)          - formater un nombre en indiquant le nombre de chiffres après la virgule à garder.
En fonction des cas, arrondis à la décimale la plus proche.

6 --> toString(1option)       - transformer un nombre en une chaîne de caractères.


// Objet Math

1 --> floor(number) - arrondit la valeur passée en paramètre à l’entier immédiatement inférieur (ou égal) à cette valeur.

2 --> ceil(number)  - arrondit la valeur passée en paramètre à l’entier immédiatement supérieur (ou égal) à cette valeur.

3 --> round(number) - arrondit la valeur passée en paramètre à l’entier le plus proche.

4 --> trunc(number) - retourner un nombre en supprimant sa partie décimale.

5 --> random(/)     - générer un nombre aléatoire décimal compris entre 0 (inclus) et 1 (exclu).
On va pouvoir multiplier son résultat par un autre nombre pour obtenir un nombre aléatoire compris dans l’intervalle de notre choix.

6 --> min(numbers,) - renvoie le plus petit nombre d’une série de nombres passés en arguments.

7 --> max(numbers,) - renvoie le plus grand nombre d’une série de nombres passés en arguments.



// Méthode sur les tableaux

1 --> push(elem,add)       - ajouter des éléments en fin de tableau et retourne la nouvelle taille du tableau.
Nous allons passer les éléments à ajouter en argument.

2 --> pop(/)               - supprimer le dernier élément d’un tableau, retourne l’élément supprimé.

3 --> shift(/)             - supprimer le premier élément d’un tableau et retourne l’élément supprimé.

4 --> unshift(elem,add)    - ajouter des éléments en début de tableau et va retourner la nouvelle taille du tableau.

5 --> splice(0 - start,
1 - second,
2 - third,)   - ajouter, de supprimer ou de remplacer des éléments n’importe où dans un tableau.

6 --> join('&'||/)         - retourne une chaîne de caractères créée en concaténant les différentes valeurs d’un tableau, vous pourrez choisir le séparateur.

7 --> slice(start/2option) - renvoie un tableau créé en découpant un tableau de départ.

8 --> concat(fusion array) - fusionner différents tableaux entre eux pour en créer un nouveau.

9 --> includes(value)      - déterminer si un tableau contient une valeur qu’on va passer en argument.



// Boucles tableaux

1 --> array.from(1para)         - créer une nouvelle instance d'Array (une copie superficielle) à partir d'un objet itérable ou semblable à un tableau.

2 --> array.isArray(1para)      - déterminer si l'objet passé en argument est un objet Array, elle renvoie true
si le paramètre passé à la fonction est de type Array et false dans le cas contraire.

3 --> array.filter(function)    - retourne un nouveau tableau contenant tous les éléments du tableau d'origine qui
remplissent une condition déterminée par la fonction callback

4 --> array.find(function)      - renvoie la valeur du premier élément trouvé dans le tableau qui respecte la condition
donnée par la fonction de test passée en argument. Sinon, la valeur undefined est renvoyée.

5 --> array.flat(/)             - créer un nouveau tableau contenant les éléments des sous-tableaux du tableau passé
en argument, qui sont concaténés récursivement pour atteindre une profondeur donnée.

6 --> array.forEach(function)   - cette boucle est une méthode de l’objet Array, elle prend en paramètre une fonction
qui contiendra le code à exécuter pour chaque valeur du tableau. Le tout ressemble
fortement à ce qu’on a l’habitude de faire pour les écouteurs d'événements ( listeners ).

7 --> array.indexOf(1para)      - renvoie le premier indice pour lequel on trouve un élément donné dans un tableau.
Si l'élément cherché n'est pas présent dans le tableau, la méthode renverra -1.

8 --> array.keys(/)             - renvoie un nouveau tableau qui contient les clés pour chaque indice du tableau.

9 --> array.values(/)           - renvoie un nouvel objet Array Iterator qui contient les valeurs pour chaque indice du tableau.

10 --> array.lastIndexOf(1para) - renvoyer le dernier indice pour lequel une valeur donnée est présente dans un tableau.
Si la valeur recherchée n'est pas présente, le résultat sera -1. Lors de la recherche, le tableau est parcouru de la fin vers le début.

11 --> array.reverse(/)         - transpose les éléments d'un tableau : le premier élément devient le dernier et le dernier devient le premier et ainsi de suite.

12 --> array.sort(/)            - trie les éléments d'un tableau, dans ce même tableau, et renvoie un nouveau tableau.
Par défaut, le tri s'effectue sur les éléments du tableau convertis en chaînes de caractères et triées.

13 --> array.map(function)      - crée un nouveau tableau avec les résultats de l'appel d'une fonction fournie sur chaque élément du tableau appelant.

14 --> array.reduce(function)   - applique une fonction qui est un « accumulateur » et qui traite chaque valeur
d'une liste (de la gauche vers la droite) afin de la réduire à une seule valeur.


// Unpack

L'affectation par décomposition (destructuring en anglais) est une expression JavaScript qui permet d'extraire
(unpack en anglais) des données d'un tableau ou d'un objet grâce à une syntaxe dont la forme ressemble à la structure du tableau ou de l'objet.


// Objet Set
Permet de stocker des valeurs uniques, de n'importe quel type, que ce soit des valeurs d'un type primitif ou des objets.

1 --> add(value)    - Ajoute un nouvel élément à l'objet Set avec la valeur donnée. La valeur de retour est l'objet Set.

2 --> clear(var)    - Retire tous les éléments de l'objet Set.

3 --> delete(value) - Retire l'élément associé à la valeur.

4 --> has(value)    - Renvoie un booléen qui indique si un des éléments de l'ensemble possède cette valeur.


// Objet Map

1 --> clear(/)           - Supprime toutes les paires de clé-valeur de l'objet Map.

2 --> delete(key)        - Supprime un élément du map, cette méthode prend en paramètre la clé de la valeur que vous souhaitez supprimer.
Renvoie true si un élément contenu dans l'objet Map existait avec cette clé et a été retiré.
Si aucun élément n'existe dans l'objet Map avec cette clé, c'est false qui est renvoyé.

3 --> forEach(value/key) - Appelle la fonction passée en paramètre ( callback ) pour chaque paire clé-valeur de l'objet Map dans leur ordre d'insertion.

4 --> get(key)           - Retourne une valeur en lui passant la clé en paramètre. Renvoie undefined s'il n'y en a pas.

5 --> has(key)           - Renvoie un booléen indiquant si une valeur associée à cette clé a été trouvée dans l'objet Map.

6 --> set(key/value)     - Définit la valeur d'une clé pour l'objet Map

7 --> keys(/)            - Renvoie un nouvel objet Iterator contenant les clés de chaque élément de l'objet Map
dans leur ordre d'insertion. Un itérateur vous permet de passer en revue les éléments avec une boucle par exemple !

8 --> values(/)          - Renvoie un nouvel objet Iterator contenant les valeurs de chaque élément de l'objet Map dans leur ordre d'insertion.