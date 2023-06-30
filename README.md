# atom-hugo-theme

atom自用hugo主题

## How to use?

There are two methods for you to install and upgrade the theme.
### Method 1

Download:

```shell
git clone https://github.com/asjdf/atom-hugo-theme themes/atom-hugo-theme --depth=1
```

Update:

```shell
cd themes/atom-hugo-theme
git pull
```

### Method 2

Download:

```shell
git submodule add --depth=1 https://github.com/asjdf/atom-hugo-theme themes/atom-hugo-theme
git submodule update --init --recursive # needed when you reclone your repo (submodules may not get cloned automatically)
```

Update:

```shell
git submodule update --remote --merge
```
