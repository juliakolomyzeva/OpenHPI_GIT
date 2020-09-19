# OpenHPI_GIT
**Create a neu repository locale and at GitHub**
1. Eine lokale Repository erzeugen
2. Eine Repository im GitHub erzeugen
3. Evtl. alte Git-Zugangsdaten local löschen (wenn man sich vorher zu einem anderen Benutzer im GitHub remotet hat )
```
git config --local credential.helper ""
```
4. (Optional) Die Remotes der lokalen Repository prüfen und wenn der alte remote nicht mehr aktuel ist löschen
```
# Remote prüfen
git remote -v

#Remote löschen
git remote remove origin
```
5. Die locale Repository remoten
```
git remote add origin https://github.com/juliakolomyzeva/OpenHPI_GIT.git
```
6. Die locale Repository pushen
```
git push --set-upstream origin master
```
