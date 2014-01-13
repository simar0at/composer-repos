composer-repos
==============

A place for repositories created for composer not to be shared on packagist yet.

Get satis using:

curl -sS https://getcomposer.org/installer | php
php composer.phar create-project composer/satis --stability=dev

Build using

php .\satis\bin\satis build .\satis.json web\

web is exported in the gh-pages branch.

So the meta-repo can be found at http://simar0at.github.io/composer-repos/