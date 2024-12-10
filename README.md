## In this file we write description of our project
## In basicstructure branch we create stack and queue 
After creating repo in git hub you foloow below steps in your local computer (VS code)

```

git remote add origin https://github.com/GunavathiGR/remote
git remote -v

git fetch origin
git merge origin/main --allow-unrelated-histories

git add .
git commit -m "local and remote are in sync now"

git push --set-upstream origin master:main

```

now we will upload branch basic structure also
```
git checkout basicstructures

git push --set-upstream origin basicstructures
git branch -vv


in other computer yu can do git clone
```

for further push and pull
```
git checkout master
git push origin master:main
```

demo commit to my student Chandana