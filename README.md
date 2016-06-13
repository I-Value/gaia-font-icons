# Gaia Font Icons

** A Font Icons based for Gaia **

## Bower
```
bower install gaia-font-icons --save
```
## Adding more icons

1. cd ~/Projetos/gaia-font-icons/


## Adding more icons
1. Add icon on /svg folder.
2. Open Terminal and run:


```sh
# Update repo
cd folder/gaia-font-icons
git pull origin master

# Generate fonts
fontcustom compile svg/

# Commit on GitHub
git add . --all
git commit -m "Name of icons added"
git push origin master

```

### Installing

#### Homebrew
```sh
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

#### fontcustom
```sh
brew install Caskroom/cask/xquartz
brew install fontforge --with-python
brew install eot-utils
gem install fontcustom

```
#### gaia-fontawesome repo
```sh
cd folder/to/save
git clone  https://github.com/I-Value/gaia-font-icons.git
```
