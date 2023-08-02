# Symfony Cine


## Installation de Symfony

### Présentation de l'arborescence

## Premier Contrôleur

## Première Vue




# Apparence

On utilisera Bootstrap, et plus précisément Darkly
**https://bootswatch.com/darkly/**

### Webpack encore

#### Installation

```bash
composer require symfony/webpack-encore-bundle
yarn install
yarn build
```

#### Ajout des dépendances graphiques


##### Font awesome

```bash
yarn add --dev @fortawesome/fontawesome-free
```

Dans le fichier **assets/styles/app.css**

```css
/* Ajout de Font Awesome */
@import '~@fortawesome/fontawesome-free/css/all.css';
```

Choix des polices:
https://fontawesome.com/v5/search?&m=free



## Datas

### Import mapping d'une BD existante

```bash
bin/console doctrine:mapping:import --path="src/Entity" App\Entity
```