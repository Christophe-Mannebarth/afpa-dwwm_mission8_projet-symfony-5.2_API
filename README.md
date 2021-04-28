Mission 8 - API REST
basée sur l'application Symfony Demo
========================

The "Symfony Demo Application" is a reference application created to show how
to develop applications following the [Symfony Best Practices][1].

Requirements
------------

  * PHP 7.2.9 or higher;
  * PDO-SQLite PHP extension enabled;
  * and the [usual Symfony application requirements][2].

Usage
-----

If you have
[installed Symfony][4] binary, run this command:

```bash
$ cd nom_du_projet/ => se placer dans le dossier de travail
$ npm (ou yarn) install => installer le dossier vendor
```

Cette release est 'buildée' donc utilisable avec Wamp ou si vous preférez utilisez le serveur de symfony:

```bash
$ cd nom_du_projet/ => se placer dans le dossier de travail
$ symfony serve -d
```

Tests
-----

Execute this command to run tests:

```bash
$ cd my_project/
$ ./bin/phpunit
```

Technologies et frameworks utilisés dans cette démo:
-----

  React
  Sass
  Symfony 5.2
  API Platform


[1]: https://symfony.com/doc/current/best_practices.html
[2]: https://symfony.com/doc/current/reference/requirements.html
[3]: https://symfony.com/doc/current/cookbook/configuration/web_server_configuration.html
[4]: https://symfony.com/download
