> "L'Informatique n'est pas plus la science des ordinateurs que l'astronomie n'est celle des télescopes." (E. Dijkstra*)  
  
Autrement dit:  
* les ordinateurs, le code, les frameworks, ... ne sont qu'un outil  
* l'Informatique est une discipline éminemment scientifique qui va au delà des outils  
* elle repose sur des concepts fondamentaux, elle repose en l'occurence sur des **éléments mathématiques** - pas d'inquiétude, rien de compliqué    
* Il y a même une philosophie de l'informatique &#128540;
> ![image](https://user-images.githubusercontent.com/5098596/229406392-28655a4f-18ce-4473-a4fa-7e3e04813c8c.png)

> *\*Edsger W. Dijkstra a reçu le Prix Turing en 1972. Le Prix Turing est considéré comme l'équivalent du prix Nobel en informatique et est décerné par l'Association for Computing Machinery (ACM). Dijkstra a reçu ce prestigieux prix en reconnaissance de ses contributions majeures à l'algorithmique, aux langages de programmation et à la philosophie de l'informatique.*  

## Contexte

### 1. Conseils préliminaires  
   * Gardez votre cerveau pour les tâches complexes.   
     
     Eliminez "l'opérationnel" en écrivant tout ce qui peut l'être: ca vous fera gagner en temps !!!  
     
     Pour se faire, je recommande trois outils: 
     * Break it down !  
       Morceller autant que faire se peut, tout problème complexe en une série de "micro" problèmes.  
       Il faut entraîner le cerveau à cela.   
     
       D'ailleurs, la "philosophie Unix" - dont je suppose que nous héritons ici - énonce deux principes fondamentaux pour la conception et le développement de logiciels. Ce sont la simplicité et le fait de faire une chose à la fois. Ces deux principes sont souvent exprimés par les énoncés suivants:

       "Faire une chose et bien la faire" (Do one thing and do it well): Ce principe suggère que chaque programme ou module doit être conçu pour accomplir une tâche spécifique et se concentrer sur cette tâche. Cela permet d'éviter la complexité et les problèmes qui pourraient résulter de la réalisation de multiples tâches dans un seul programme.  

       "La simplicité est la clé" (Keep it simple, stupid - KISS): Ce principe encourage les développeurs à créer des logiciels simples et faciles à comprendre. Les systèmes simples sont souvent plus faciles à maintenir, à déboguer et à améliorer.  
       
       ![image](https://user-images.githubusercontent.com/5098596/229467425-d78bdb7e-4f52-4afd-9bca-33fb6e03aa9c.png)

       
     * L'utilisation des flowcharts    
       ![image](https://user-images.githubusercontent.com/5098596/229406972-721bc86b-3dad-497d-9c86-8c88812a08c4.png)
       
       *Remarque* :   
       *Utilisez des symboles standard pour représenter les différentes étapes et éléments du flowchart.  
        Par exemple, **les rectangles pour les processus, les losanges pour les décisions, les cercles pour les points de départ et d'arrivée**, et les flèches pour indiquer la direction du flux.  
        Gardez le flowchart aussi simple que possible. Évitez les détails inutiles et concentrez-vous sur les étapes clés et les décisions importantes. Si un processus est trop complexe, envisagez de le décomposer en sous-processus ou en sous-flowcharts.*    
        
       
     * L'utilisation de pseudo-code   
       Le pseudo-code, c'est écrire du code dans un langage humain: avec des phrases et des mots intelligibles.  
     
   * Appuyez vous sur des modèles mathématiques.  
   
     Les modèles mathématiques sont partout, et faire l'effort de les (re)onnaître confère un niveau d'abstraction indispensable pour créer toute chose complexe. 
     Exemples:  
     la théorie des graphes sous-tend tous les réseaux sociaux:  

     ![image](https://user-images.githubusercontent.com/5098596/229405645-cec2efbd-773b-4daa-9fcb-cf37d969ebcc.png)

     la loi de Poisson est omniprésente dans le Data Science et le Machine Learning, et donc dans l'IA.  
     
     ![image](https://user-images.githubusercontent.com/5098596/229472241-0afe22f1-54d0-400b-b5a9-5da43baa07ef.png)

     
     La distribution de Poisson est un concept mathématique utilisé pour décrire le nombre d'événements qui se produisent dans un intervalle de temps ou d'espace fixe. Elle est utile dans le domaine de l'intelligence artificielle (IA) pour modéliser et prédire des situations où des événements rares ou aléatoires se produisent.  
   
     
### 2. La Logique  
La logique est une compétence essentielle pour la programmation, car elle aide à comprendre comment résoudre des problèmes et à prendre des décisions en utilisant des règles et des principes.   

### 3. Mieux compter  
3.1. Multiplication  
* si un event a lieu n fois, et un autre event a lieu m fois, la probabilité que les deux events arrivent est: **m x n** fois 
  
  **EXERCICE:**  &#128520;
  > Un code PIN est composé de 2 nombres et de 1 lettre. Ca prend une seconde pour essayer un PIN.  
  > Dans le pire des cas, de combien de temps a-t-on besoin pour cracker un PIN ?  

  **EXERCICE:**  &#128520;
  > Il y a 23 candidats qui veulent rejoindre ton equipe.  
  > Pour chaque candidat, tu joues a PILE ou FACE et tu n'engage que quand c'est PILE.  
  > Combien de combinaisons d'équipe sont possibles ?  

3.2 Permutations  
La permutation , c'est le nombre de facons dont on peut arranger ou ordonner quelquechose.  
supposons que nous avons n entités.  
De combien de facons peut on choisir 1 entité parmi les n ? Ensuite, si le premier est choisi, de combien de facons peut on chosiir une seconde entité ? Ensuite si le second est choisi, de combien de facons peut on choisir une troisième entité ? etc ...  
Cela s'exprime par la **factorielle**  
**n! = n x (n-1) x (n-2) x (n-3) x ... x 1**  

