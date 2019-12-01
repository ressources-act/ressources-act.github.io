# ressources-act
Repo pour site web de l'organisation Github.

# Contributions
Se référer à la procédure de contribution du Guide de survie en actuariat.

# Déploiement
Le déploiement est automatisé sur la branche `master` à l'aide de Netlify. Du moment qu'un nouveau commit est fait sur `master`, le [site web](https://ressources-act.netlify.com) est mis à jour.


# Publications

```r
# Générer un "squelette" d'article
blogdown::new_post(title = "nom de l'article", author = 'mon nom', 
                   tags = c('tag1', 'tag2'), categories = c('cat1', 'cat2'),ext = '.Rmd')
# Générer un contenu (plus général)
blogdown::new_content('contrib.md')
```