# Hugo Base Config

Base config for Hugo.

## Install

```sh
git submodule add 'https://github.com/pkgstore/hugo-cfg-base.git' 'config/_default'
```

## Update

```sh
git submodule update --remote --merge
```

## Uninstall

```sh
m='_default'; git submodule deinit -f "config/${m}"; git rm -r --cached "config/${m}"; rm -rf ".git/modules/config/${m}"; rm -rf "config/${m}"
```
