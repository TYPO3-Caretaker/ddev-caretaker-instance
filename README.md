# ddev Setup for Caretaker Instance

## installation

* Install docker and ddev (https://ddev.readthedocs.io/en/latest/)
* clone repo and start ddev projekt:

```
git clone https://github.com/TYPO3-Caretaker/ddev-caretaker-instance.git && \
cd ddev-caretaker-instance && \
git submodule init && \
git submodule update && \
ddev start && \
open https://ddev-caretaker-instance.ddev.site/typo3/install/
```

Login with "password" and create your backend user.
