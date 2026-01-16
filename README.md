Classification sur MNIST avec seulement 100 images annotées. 

Comparaison de deux méthodes :

- Modèle baseline (CNN d'architecture personnalisée) entrainé directement sur les 100 images annotées.
        
- Encodeur de même architecture pré-entrainé sur 49900 images non-annotées via la méthode SimCLR (non-supervisée). Puis linear probing avec les 100 images annotées.
