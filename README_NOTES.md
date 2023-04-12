
(StarterKit Theme)[https://www.drupal.org/docs/core-modules-and-themes/core-themes/starterkit-theme]

(Debugging twig templates)[https://www.drupal.org/docs/theming-drupal/twig-in-drupal/debugging-twig-templates]

(Twig Debugger module)[https://www.drupal.org/project/twig_debugger]

```
composer require 'drupal/twig_debugger:^1.1'
```

(TWIG DOCS)[https://twig.symfony.com/doc/3.x/templates.html]
(TWIG DRUPAL FUNCTIONS)[https://www.drupal.org/docs/theming-drupal/twig-in-drupal/functions-in-twig-templates]

## Install drush

https://drupalize.me/tutorial/install-drush-using-composer?p=3516
./vendor/bin/drush list

## Export config

https://www.drush.org/latest/commands/config_export/
./vendor/bin/drush config:export

## Backup

./vendor/bin/drush archive:dump
./vendor/bin/drush archive:dump --destination=/path/to/archive.tar.gz --overwrite --exclude-code-paths=web/sites/default/settings.php

## Drush Rebuild cache
./vendor/bin/drush cache:rebuild

## SSH Connect
```
ssh -i C:\Users\alopez09\keys\isobarDesa isobar@172.30.3.211
```

```
sudo /usr/local/bin/composer require 'drupal/twig_debugger:^1.1'
```

Dar propiedad a apache
```
sudo chown -R apache *
```

```
sudo mysql
create database <nombre_database>;
GRANT ALL PRIVILEGES ON <nombre_database>.* TO 'desa'@'localhost' WITH GRANT OPTION;

```


## DB user
desa / desap4ss

## DRUPAL user
admin / nurun007