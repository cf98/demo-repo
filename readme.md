# Demo

Some text here!

## Some notes

`git status` shows the file that has been changed.
The same output will also show the untracked files. Like the index.html we just added.

We can use `git add` to add this. Or use `git add .` to track everything in current directory.

`git committ` save things locally. `-m` to show title, add another `-m` to add decription.
`git push` will have it pushed to remote host.

the public key "testkey.pub" is the one you put on github.

**It's important that everytime you need to git add before git commit.**

## ssh key
First set up the config according to [this website](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent). 
Then use the command to add it.
```zsh
ssh-add --apple-use-keychain testkey
```