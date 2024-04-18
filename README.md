
police d'écriture

icône

<i class="fa fa-heart" aria-hidden="true"></i>
Copiez l'intégralité font-awesomedu répertoire dans votre projet.
Dans <head>votre code HTML, référencez l'emplacement à votre font-awesome.min.css.
<link rel="stylesheet" href="path/to/font-awesome/css/font-awesome.min.css">
Consultez les exemples pour commencer à utiliser Font Awesome !
Utiliser Sass ou moins
Utilisez cette méthode pour personnaliser Font Awesome 4.7.0 en utilisant Less ou Sass.

Copiez le font-awesome/répertoire dans votre projet.
font-awesome/less/variables.lessOuvrez le ou de votre projet font-awesome/scss/_variables.scsset modifiez la variable @fa-font-pathou $fa-font-path pour pointer vers votre répertoire de polices.
@fa-font-path:   "../font";
Le chemin de la police est relatif à partir de votre répertoire CSS compilé.

Recompilez votre Less ou Sass si vous utilisez un compilateur statique. Sinon, vous devriez être prêt à partir.
Consultez les exemples pour commencer à utiliser Font Awesome !
ou
Avancé et forfaitsPro
Moins de rubis
Utilisez le Ruby Gem officiel de Font Awesome Less pour intégrer facilement Font Awesome Less dans un projet Rails. Généreusement entretenu par @supercodepoet .

Ajoutez cette ligne au Gemfile de votre application :
gem 'font-awesome-less'
Et puis exécutez :
$ bundle
Ou installez-le vous-même en tant que :
$ gem install font-awesome-less
Si vous utilisez Rails, ajoutez ceci à votre exempleapplication.less :

@import "font-awesome-sprockets";
@import "font-awesome";
Gemme rubis impertinente
Utilisez le Ruby Gem officiel de Font Awesome pour intégrer facilement Font Awesome Sass dans un projet Rails ou Compass. Généreusement entretenu par @supercodepoet .

Ajoutez cette ligne au Gemfile de votre application :
gem 'font-awesome-sass'
Et puis exécutez :
$ bundle
Ou installez-le vous-même en tant que :
$ gem install font-awesome-sass
Si vous utilisez Rails, ajoutez ceci à votre exempleapplication.scss :

@import "font-awesome-sprockets";
@import "font-awesome";

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css
