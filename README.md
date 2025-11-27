Pour ajouter un sous-module

- Ajouter un repository
  
```
cd NewModule
git add .
git commit -m "Initial commit"
cd ..
git submodule add https://github.com/jcgagne2/NewModule.git NewModule
```
