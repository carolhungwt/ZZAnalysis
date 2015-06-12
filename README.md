ZZAnalysis
==========

To install a complete CMSSW area (including this package)
------------------------------
Download and execute the setup script for the given release:

*   For CMSSW_7_4_5:

    ```
    wget -P /tmp https://raw.githubusercontent.com/CJLST/ZZAnalysis/miniAOD_74X/checkout_70X.csh
    cd $CMSSW_BASE/src
    cmsenv
    source /tmp/checkout_70X.csh
    ```

To update this package from the release
------------------------------------------
In the package directory, simply issue
```
git pull
```

To commit and push new changes:
------------------------------
To commit directly (you need write access to the repository):
```
git pull
[edit files]
```
Once you are ready to commit
```
git pull
git add [files to be added]
git commit -m ["commit message"] [files to be added]
git push origin master
```

Otherwise you can make a fork of the repository, develop therein, and make a pull request in the same way as for CMSSW.
