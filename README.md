# NLP-Rule-based-Regex-NLP-Word-embedding
Ce projet vise à démontrer les techniques de traitement automatique du langage naturel (NLP), y compris le NLP basé sur des règles, l'expression régulière et les vecteurs de mots. Les tâches suivantes ont été effectuées :

# Partie 1 : NLP basé sur des règles et expression régulière
Un code Python a été écrit pour générer une facture à partir d'un texte donné par l'utilisateur. Le code utilise des expressions régulières pour identifier les noms de produits, les quantités et les prix unitaires, puis calcule le prix total pour chaque article. Le code gère à la fois les quantités numériques et les mots de quantité (par exemple, "un", "deux").

## Exemple d'utilisation :

user_text = "I bought three Samsung smartphones 150 $ each, four kilos of fresh banana for 1,2 dollar a kilogram and one Hamburger with 4,5 dollar"

generated_bill = generate_bill(user_text)

print("Generated Bill:\n", generated_bill)


# Partie 2 : Vecteurs de mots
## Tâche 1 : Encodage One Hot, sac de mots et TF-IDF
L'encodage One Hot, le sac de mots et TF-IDF ont été appliqués aux vecteurs de données collectés lors du laboratoire.

## Tâche 2 : Word2Vec (Skip Gram et CBOW)
Word2Vec avec les approches Skip Gram et CBOW a été appliqué au jeu de données.

## Tâche 3 : GloVe et FastText
GloVe et FastText ont également été appliqués au jeu de données.

## Tâche 4 : Visualisation t-SNE
Les vecteurs encodés/vectorisés ont été tracés à l'aide de l'algorithme t-SNE pour la visualisation. Les approches suivantes ont été évaluées :

Encodage One Hot
Sac de mots
TF-IDF
Word2Vec (Skip Gram et CBOW)
GloVe
FastText
Un résumé général a été fourni sur la base de l'évaluation de ces techniques.

## Tâche 5 : Visualisation t-SNE des vecteurs de mots en 3D
Les vecteurs de mots ont été visualisés en 3D à l'aide de t-SNE.


# Conclusion
Ce projet démontre diverses techniques de traitement automatique du langage naturel, y compris le NLP basé sur des règles, l'expression régulière et les vecteurs de mots. Les résultats montrent que les vecteurs de mots, tels que Word2Vec, GloVe et FastText, capturent les relations sémantiques entre les mots, ce qui les rend appropriés pour les tâches NLP. TF-IDF est utile pour représenter l'importance des mots dans un document.
