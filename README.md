# haskell-templates

personal opinionated templates for working with Haskell

## Setup default template

Edit your `~/.stack/config.yaml` and add a default-template:

```yaml
# other stuff
...
default-template: https://github.com/enolive/haskell-templates/raw/master/tdd.hsfiles
```

## TDD

Basic Setup to start doing TDD with Haskell

```
stack new my-cool-app https://github.com/enolive/haskell-templates/raw/master/tdd.hsfiles
```
