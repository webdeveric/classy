# Wordpress theme boilerplate
Light, well-structured wordpress theme boileplate based on “Laravel Blade” template engine

### Why Blade?

Blade is the simple, yet powerful templating engine provided with Laravel. Unlike other popular PHP templating engines, Blade does not restrict you from using plain PHP code in your views. All Blade views are compiled into plain PHP code and cached until they are modified, meaning Blade adds essentially zero overhead to your application.

### What’s about structure?

The biggest problem with wordpress theme development is that you always need to repeat same code.  New approach, that assumes that template data will be collected and prepared separately from actual render allows you to have the project structured more accurate.

### How it works?

TemplateLoader repeats the wordpress template hierarchy and uses it separately for scopes and templates. This allows to use the same scope with different templates and different scopes with the same template.

## Instalation
1. Navigate to your WordPress themes directory
`$ cd ~/Sites/mysite/wp-content/themes`
2. Clone repository `$ git clone git@github.com:anrw/wp-scratch-theme.git`
3. Navigate `cd wp-scratch-theme`
4. Run install `gulp install`


# Requirements:

PHP: 5.4+