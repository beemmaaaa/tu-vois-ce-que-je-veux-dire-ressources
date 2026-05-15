# Tu vois ce que je veux dire — Ressources

Page ressource autonome liée à l’expérience **Tu vois ce que je veux dire**. Elle sert de prolongement après le parcours principal, avec des comptes, médias et outils pour continuer à s’informer, décrypter les discours et vérifier ses sources.

## Objectif

La page accompagne l’utilisateur après l’expérience interactive. Elle rappelle qu’une vidéo, un média ou un format court peut orienter le regard, et invite à garder son esprit critique : aucun média n’est 100% neutre.

Les ressources sont organisées en trois temps :

- **S’informer** : comptes et médias accessibles pour suivre l’actualité.
- **Décrypter** : contenus pour comprendre les biais, la rhétorique, l’influence et la manipulation.
- **Expérimenter** : outils concrets pour comparer des idées ou participer à des démarches citoyennes.

## Fichiers

- `index.html` : page complète, avec HTML et CSS intégrés.

La page ne dépend d’aucun framework, d’aucune installation et d’aucun serveur local. Elle peut être ouverte directement dans un navigateur.

## Ouvrir la page

Double-cliquer sur `index.html`, ou l’ouvrir dans un navigateur moderne.

## Direction artistique

La page reprend les codes visuels du projet principal dans une version plus légère :

- fond clair `#FCF3FF`,
- texte principal sombre,
- accent violet `#A6A3ED`,
- touches cyan, rose et violet pour différencier les catégories,
- halos discrets sur certains éléments d’interface,
- cards aérées, sans cadres lourds.

## Modifier le contenu

Les ressources sont dans le corps du fichier, sous forme de blocs :

```html
<article class="card">
  ...
</article>
```

Pour ajouter une ressource, dupliquer une card existante, puis modifier :

- les initiales dans `.avatar`,
- le nom dans `.card-name`,
- la description dans `.card-desc`,
- les liens dans `.chips`.

Les boutons utilisent des classes pour garder un code couleur :

- `chip-yt` : YouTube,
- `chip-ig` : Instagram,
- `chip-tt` : TikTok,
- `chip-web` : site web,
- `chip-app` : application.

## Modifier le style

Le CSS est directement dans la balise `<style>` de `index.html`.

Les réglages les plus utiles sont dans la dernière partie du CSS, à partir du commentaire :

```css
/* Version lumineuse : fond clair, sans cadre ni pixels decoratifs */
```

C’est là que se trouvent les couleurs, le fond clair, les halos, les cards et les styles de liens.

## Déploiement

Comme la page est autonome, il suffit de publier `index.html` tel quel sur un hébergement statique ou de l’ajouter au projet principal comme page de sortie / ressources.

## Note éditoriale

Les liens proposés ne sont pas une validation absolue des contenus. Ils sont pensés comme des points d’entrée pour croiser les sources, comparer les formats et développer une lecture critique de l’information.
