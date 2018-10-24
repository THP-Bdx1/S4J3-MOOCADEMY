

Ce projet a été réalisé par la Team 1 Bordeaux, à savoir :

    François,
    Valérian,
    Paul,
    David,
    William

Il reflète la structure de TMOOCademy. Il comporte une base de données :

    Course. Chaque cour a un nom (name, généré avec un langage informatique aléatoire issu de la banque de donnée faker) et une description (description, générée avec des quotes de Rick et Morty), chaque cour a plusieurs lessons associées.
    Lesson. Chaque lesson est associée a un cours (course_id), et possède un titre (title, une des villes des jeux the Elders Scrolls) et une description (body, une phrase en wookie).

Lancez un "bundle install" pour installer les différentes gem, dont Faker qui est ici utilisé pour générer des bases de données aléatoires.

N'hésitez pas à lancer un petit "rails db:reset" pour une nouvelle base de donnée aléatoire toute fraîche ;)
