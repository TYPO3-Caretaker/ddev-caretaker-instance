# ddev Setup for Caretaker Instance

## install

```
git clone git@github.com:TYPO3-Caretaker/ddev-caretaker-instance.git
cd ddev-caretaker-instance
ddev start
ddev import-db --src=db.sql
open http://caretaker-instance.ddev.local/typo3/
# use admin / password for BE Login
```

