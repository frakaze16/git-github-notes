# 13 Advanced (but useful) Git Techniques and Shortcuts

[video](https://youtu.be/ecK3EnyGD8o)




## Combine add & commit

`git add .`
`git commit -m "hi mom"`

`git commit -am "that was easy"` 😎




## Aliases

`git config --global alias.ac "commit -am"`




## Amend

`git commit -m "ncie!"` ❌

Change message of **last commit**

`git commit --amend -m "nice!"` 😎

***

`git add .`

**Add files** to last commit

`git commit --amend --no-edit`




## Force push, revert, codespaces > 

*2:02*




## Stash

Save in pocket 👌

*3:20*




## Master branch

**master** = default branch

**main, mega, mucho** 💚




## Log

`git log --graph --oneline --decorate`




## Bisect, autosquash, hooks, destruction

*4:50*




## Bonus

Goto previous branch

`git checkout -`