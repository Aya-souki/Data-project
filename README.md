# Data-project
Automatic login, download of datasets, and SQL database connexion and update. I used a click automation robot to download datasets and run a data cleaning and table separating algorithm (to obtain a relational database) then log in to SQL and update tables automatically.
Languages used: Python, SQL
Computing platform: Jupiter Notebook

Ceci est un projet de base de données sur lequal j'ai travaillé. La bibliothèque de notre école ayant un site (private) où les prêts sont enregistrés, ma mission a été de créer un robot (avec Python et ses bibliothèques) qui permettra de réaliser le login et de télécharger les fichiers csv. Une fois ceci fait, ces fichiers doivent être traités pour construire une base de données relationnelle suivant une architecture conçue au préalable (d'où le fichier cleaning). Le robot réalisera après l'update des tables sur SQL à partir de ces fichiers csv, ce qui nous permettra de construire par la suite un système de recommandation par filtrage collaboratif (SVD) au service des élève, en leur permettant aussi de connaître la disponibilité des livres et de les réserver. J'ai mis du temps à supprimer les informations confidentielles (login...) mais l'essentiel (code du robot, construction de la base de données relationnelle et conception, commandes SQL) est regroupé dans ce fichier ZIP.

