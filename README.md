# phpenv-update-all

This [phpenv](https://github.com/phpenv/phpenv) plugin adds the `phpenv update-all` command that updated phpenv and all installed plugins.  
Forked from [Konstantin Haase](https://github.com/rkh)'s [rbenv-update](https://github.com/rkh/rbenv-update).

Renamed to `phpenv update-all` command as it conflicts with [php-build](https://github.com/php-build/php-build)'s `phpenv update` command.

## Installation

Simply clone the repository into the plugins directory:

```shell
mkdir -p "$(phpenv root)/plugins"
git clone https://github.com/matayoshi/phpenv-update-all.git "$(phpenv root)/plugins/phpenv-update-all"
```

## Usage

```shell
phpenv update-all
```
