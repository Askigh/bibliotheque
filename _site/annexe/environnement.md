# Environnement de travail en local

## Voici les prérequis pour travailler sur le site en local

1. Avoir Ruby installé sur votre machine. Si ce n'est pas le cas je vous redirige vers [le site de ruby](https://www.ruby-lang.org/en/downloads/)
2. Une fois l'installation de Ruby effectuée il vous faudra installer Bundler
    - ```code
        gem install bundler
        ```
3. Une fois Bundle installé il faut que vous installiez les différentes dépendances
    - ```code
        bundle install
        ```
4. Une fois les étapes précèdentes complétées, vous pouvez lancer le site en local avec la commande suivante :
    - ```code
        bundle exec jekyll serve
        ```