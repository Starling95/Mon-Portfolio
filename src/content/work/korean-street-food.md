---

title: Korean Street Food
publishDate: 2020-03-02 00:00:00
img: /assets/korean-street-food.png
img_alt: screen accueil blog
description: Projet personnel d'un blog culinaire portant sur la cuisine de rue Sud-Coréenne

tags:
  - Design
  - Dev
  - Symfony
---
## Travail effectué
J’ai conçu un blog culinaire, ayant pour sujet la cuisine de rue Sud-Coréenne. J’ai utilisé le framework Symfony.
- J’installe PHP.
- Ensuite je dois installer Composer, qui est un gestionnaire de dépendances pour PHP. Dans le terminal j’exécute composer global require symfony/cli .
- Une fois l’installation terminée, je créer mon projet en utilisant la commande symfony new suivi du nom de mon projet.
- Je configure mon serveur web pour pointer vers le répertoire public de mon projet Symfony. Cela garantira que les requêtes HTTP soient correctement dirigées vers l'application Symfony.
- Je configure les paramètres de base de données dans le fichier .env de mon projet pour spécifier le type de base de données, l'hôte, le nom de la base de données, l'utilisateur et le mot de passe. 
- Je créer une entité en utilisant  la commande make:entity pour générer une entité et pour représenter les données que l’application utilisera.
- Pour faire la migration de base de données, donc pour mettre à jour ma base de données j’utilise la commande make:migration et j’applique ces migrations avec la commande doctrine:migrations:migrate.
- Pour gérer les actions de mon application, j’utilise la commande make:controller.
- Pour afficher les données, je créer des vues en utilisant le moteur de templates Symfony (Twig).
> 
Sur ce blog, la page d’accueil contient une brève description, un carousel réalisé en JavaScript et un pied de
page contenant un lien vers la page de politique de confidentialité et la page contact.
> 
L’utilisateur peut consulter les recettes et grâce à un formulaire, il peut travailler en tant que blogueur culinaire s’il le souhaite.
>
- Réalisation d’un blog culinaire sur la cuisine de rue Coréenne 
- Codage d’un carousel et importation d’images 
- Codage de formulaire, pages recettes
- Création de la BDD 


### Moyen utilisés
    • Framework : Symfony 6 - Bootswatch
    • PHPmyAdmin
    • Composer
    • Htmltwig 
    • PHP  
    • CSS 
    • JavaScript




<video width="1000" height="500" controls
  src="/assets/korean-street-food-home.mp4"
  type="video/mp4">
  korean-street-food-home
</video>
