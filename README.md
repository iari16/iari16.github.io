# TIPE Iari Metayer-Mendoza

## Sujet probable : comment régler le probleme de dérive de position et bruit de signal GPS.

7/03/25 : 
  Idée : filtre de Kalman, utiliser des graphes pour représenter les déviation des GPS, utiliser des données réelles pour faire mes propres     tests.

14/03/25 : J'ai trouvé une bonne page explicative sur le philtre de Kalman qui permettrait de faire du tracking d'un objet mobile avec un outil ou capteur qui donne sa position de façon récurrente, et ce afin d'améliorer les informations fournies par le capteur qui peuvent être quelques fois de mauvaises qualitées car bruitées. [Ici](https://github.com/Hamedkiri/Filtre-de-Kalman) le lien
) le lien.


Idée : coder moi même un filtre de Kalman sur phyton afin d'améliorer les signaux GPS bruts que j'aurais moi même pris, soit par l'intermédiaire d'une base de donnée, soit directement à partir d'un appareille personnel. Le but de filtre va être de recrée un itinéraire cohérent avec la réalité.
