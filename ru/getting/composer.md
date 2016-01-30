# Установка Drupal Console с помощью Composer
Вы можете установить этот проект используя composer.

## Установка Drupal Console глобально с помощью composer:
```
$ composer global require drupal/console:@stable
```

## Add the binary directory to your class path:
```
$ echo "PATH=$PATH:~/.composer/vendor/bin" >> ~/.bash_profile
```

## Теперь вы можете запустить Drupal Console:
```
$ drupal generate:module
```
