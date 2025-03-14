# TIPE Iari Metayer-Mendoza

## Sujet probable : comment régler le probleme de dérive de position et bruit de signal GPS.

7/03/25 : 
  Idée : filtre de Kalman, utiliser des graphes pour représenter les déviation des GPS, utiliser des données réelles pour faire mes propres     tests.

14/03/25 : J'ai trouvé une bonne page explicative sur le philtre de Kalman qui permettrait de faire du tracking d'un objet mobile avec un outil ou capteur qui donne sa position de façon récurrente, et ce afin d'améliorer les informations fournies par le capteur qui peuvent être quelques fois de mauvaises qualitées car bruitées. [Ici](https://github.com/Hamedkiri/Filtre-de-Kalman) le lien.

Idée : coder moi même un filtre de Kalman sur phyton afin d'améliorer les signaux GPS bruts que j'aurais moi même pris, soit par l'intermédiaire d'une base de donnée, soit directement à partir d'un appareille personnel. Le but de filtre va être de recrée un itinéraire cohérent avec la réalité.

Découverte du SNR (Signal-to-noise ratio) qui est un outil qui permet de mésurée la qualité d'un signal en faisant le rapport de la puissance du signal par rapport au bruit. Une très bonne thèse [ici](https://theses.hal.science/tel-01589215v1/file/BOURKANE_Abderrahim.pdf) sur ce sujet. Je pourrais faire un algo qui calcul le SNR de chaque signal brut que j'ai afin de calibrer mon filtre de Kalman en conséquence.

Phénomène Doppler à développer, ça parait être un outil intéressant pour l'amelioration du signal GPS. Toujours expliqué dans la thèse.
