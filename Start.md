# Slik begynner du!

* Start et prosjekt på linken [https://git.errorsparty.no/projects/new]









### Command line instructions
#### Git global setup

```
git config --global user.name "Marius"
git config --global user.email "marius-solberg@hotmail.com"
```

#### Create a new repository

```
git clone ssh://git@git.errorsparty.no:1337/Git_Guide/Git_Wiki.git
cd Git_Wiki
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master
```

#### Existing folder

```
cd existing_folder
git init
git remote add origin ssh://git@git.errorsparty.no:1337/Git_Guide/Git_Wiki.git
git add .
git commit -m "Initial commit"
git push -u origin master
```

#### Existing Git repository

```
cd existing_repo
git remote rename origin old-origin
git remote add origin ssh://git@git.errorsparty.no:1337/Git_Guide/Git_Wiki.git
git push -u origin --all
git push -u origin --tags
```