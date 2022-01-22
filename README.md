# phpenv-update

This [phpenv](https://github.com/phpenv/phpenv) plugin adds the `phpenv update` command that updated phpenv and all installed plugins.  
Forked from [Konstantin Haase](https://github.com/rkh)'s [rbenv-update](https://github.com/rkh/rbenv-update).

## Installation

Simply clone the repository into the plugins directory:

```shell
mkdir -p "$(phpenv root)/plugins"
git clone https://github.com/matayoshi/phpenv-update.git "$(phpenv root)/plugins/phpenv-update"
```

## Usage

```shell
phpenv update
```
