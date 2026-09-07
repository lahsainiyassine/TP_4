Exercice 1 : Gestion d'un étudiant et tableau dynamique de notes
* Modélisation de la classe `Etudiant` avec génération automatique d'identifiants uniques via un compteur `static`.
* Implémentation d'un tableau redimensionnable manuellement avec `System.arraycopy()` pour pallier la taille fixe initiale.
* Calcul arithmétique de la moyenne des notes et formatage de la méthode `toString()`.

https://github.com/user-attachments/assets/7da50df9-1ae4-4309-a2ca-c11cb570b88f

 Exercice 2 : Association bidirectionnelle Filière ↔ Étudiants
* Mise en place d'une relation un-à-plusieurs ($1 \dots *$) gérée intégralement par un tableau natif `Etudiant[]`.
* Redimensionnement automatique de la capacité d'accueil de la filière lors de l'ajout d'étudiants.
* Synchronisation réciproque de la référence de filière au sein de l'objet étudiant (`e.setFiliere(this)`).

https://github.com/user-attachments/assets/ac91d263-c407-4abc-870b-8d7b6a4d66ca

Exercice 3 : Gestion des Articles et Catégories (Architecture en packages)
* Organisation du projet selon deux packages distincts : `ma.projet.bean` (métier) et `ma.projet.test` (exécution).
* Association simple d'un article à sa catégorie parente avec identifiants auto-incrémentés.
* Parcours croisé et filtrage d'affichage par catégorie à l'aide de boucles classiques et de tableaux statiques.


https://github.com/user-attachments/assets/f721a0dc-596a-4425-a676-bd1452989534

Exercice 4 : Associations multiples (Auteur, Livre, Bibliothèque)
* Gestion d'une association $1 \dots *$ entre `Auteur` et `Livre` à l'aide d'une collection `List<Livre>`.
* Prise en charge d'une association plusieurs-à-plusieurs ($* \dots *$) entre `Bibliotheque` et `Livre`.
* Utilisation d'un ensemble `Set<Livre>` pour garantir l'unicité des ouvrages au sein d'une bibliothèque.

https://github.com/user-attachments/assets/f9beb3bf-ab0e-4a39-90d8-7e4f85dcfa35


