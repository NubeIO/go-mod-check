# go-mod-check
a small py script to compare and update go.mod files


# usage for for comparing

will show you any differences

```
python3 check.py /home/aidan/code/go/test/repo1 /home/aidan/code/go/test/repo2 
github.com/NubeIO/rxclient:
ERROR: repo1: v0 | repo2: v0.0.2  
```


# usage for updating
```
python3 check.py /home/aidan/code/go/test/repo1 /home/aidan/code/go/test/repo2 --update-repo github.com/NubeIO/reactive --update-version v1.21111
Updated github.com/NubeIO/reactive to version v1.21111
REPO: repo1  existing-version: v1.21   new-version: v1.21111    
REPO: repo1  existing-version: v1.21   new-version: v1.21111  
```
