PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> git branch
* main
PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> git remote
origin
PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> git remote -v
origin  https://github.com/imranjia/LocalRepoOfis.git (fetch)
origin  https://github.com/imranjia/LocalRepoOfis.git (push)
PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> 
git branch -m main
git 

PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> git branch
* main
PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> git remote
origin
PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> git remote -v
origin  https://github.com/imranjia/LocalRepoOfis.git (fetch)
origin  https://github.com/imranjia/LocalRepoOfis.git (push)
PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Gitcommands.md

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> git add .\Gitcommands.md
PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> git status

PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> git checkout -b feature1
Switched to a new branch 'feature1'
PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> git branch
* feature1
  main
PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> git checkout main
M       Gitcommands.md
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)
PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> git branch
  feature1
* main
PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> git checkout feature1
M       Gitcommands.md
Switched to branch 'feature1'
PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> git branch

PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> git checkout -b feature2
Switched to a new branch 'feature2'
PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> git branch
  feature1
* feature2
  main
PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> git branch -d feature2
error: cannot delete branch 'feature2' used by worktree at 'C:/Users/AhmedImran/My Drive/2025 Learn/ImranPython2025/LocalRepoOfis'
PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> git checkout feature1
M       Gitcommands.md
Switched to branch 'feature1'
PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> git branch
* feature1
  feature2
  main
PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> git branch -d feature2
Deleted branch feature2 (was 8c4ed71).
PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> git branch
* feature1
  main
PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> 

PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> git branch
  feature1
* main
PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> git pull origin main
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (2/2), 964 bytes | 53.00 KiB/s, done.
From https://github.com/imranjia/LocalRepoOfis
 * branch            main       -> FETCH_HEAD
   72f5e12..0eb9eb4  main       -> origin/main
Updating 72f5e12..0eb9eb4
Fast-forward
 Readme.md | 3 ++-
 1 file changed, 2 insertions(+), 1 deletion(-)
PS C:\Users\AhmedImran\My Drive\2025 Learn\ImranPython2025\LocalRepoOfis> 

