# Git basics

# Level 1.1   
```
git commit
git commit
```

# Level 1.2
```
git branch bugFix
git checkout bugFix
```

# Level 1.3
```
git checkout -b bugFix
git commit
git checkout master
git commit
git merge bugFix
```

# Level 1.4
```
git checkout -b bugFix
git commit
git checkout master
git commit
git checkout bugFix
git rebase master
```

# Level 2.1
```
git checkout c4
```

# Level 2.2
```
git checkout bugFix^
```

# Level 2.3
```
git branch -f master C6
git checkout HEAD~1
git branch -f bugFix HEAD~1
```

# Level 2.4
```
git reset HEAD~1
git checkout pushed
git revert HEAD
```
# Level 3.1
```
git cherry-pick C3 C4 C7
```

# Level 3.2
```
 git rebase -i HEAD~4 --aboveAll
```

# Level 4.1
```
git checkout master
git cherry-pick C4
```

# Level 4.2
```
git rebase -i HEAD~2
git commit --amend
git rebase -i master
git branch -f master caption
```
# Level 4.3
```
git checkout C2
git commit --amend
git checkout master
git cherry-pick C2' C3
```

# Level 4.4
```
git tag v0 C1
git tag v1 C2
git checkout v1
```

# Level 4.5
```
git describe master
git describe side
git commit
```
# Level 5.1
```
git rebase side another
git rebase bugFix another
git rebase master another
git branch -f master another
```
# Level 5.2
```
git branch -f bugWork HEAD~^2~
```
# Level 5.3
```
git checkout one
git cherry-pick C4 C3 C2
git checkout two
git cherry-pick C5 C4 C3 C2
git branch -f three C2
```
# Screenshot of Git Levels

![](https://cloud.githubusercontent.com/assets/11032855/9749636/d708fc98-565c-11e5-9b65-95f935040371.png)

# Hooks

![hw0](https://cloud.githubusercontent.com/assets/11032855/9750613/1ca9a300-5668-11e5-9fdd-1b29704ab81b.gif)

# Content of post-commit
```
#!/bin/bash

open https://github.com/gsrajadh/Devops-HW
```
