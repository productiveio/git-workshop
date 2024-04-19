# Config

* How to setup config
* [core] global git ignore
* [core] ignorecase
* [core] editor when commit
* [core] diff-so-fancy
* [push] default
* [push] autoSetupRemote
* [merge] mergetool
* [pull] rebase or not
* [rebase] autostash
* [rebase] autosquash
* [rebase] rerere
* [init] defaultBranch

# Aliases ?

# Log
```sh
export _git_log_medium_format='%C(bold)Commit:%C(reset) %C(green)%H%C(red)%d%n%C(bold)Author:%C(reset) %C(cyan)%an <%ae>%n%C(bold)Date:%C(reset)   %C(blue)%ai (%ar)%C(reset)%n%+B'
export _git_log_oneline_format='%C(green)%h%C(reset) %s%C(red)%d%C(reset)%n'
gl='git log --topo-order --pretty=format:"$_git_log_medium_format"'
gld='git log --topo-order --stat --patch --full-diff --pretty=format:"$_git_log_medium_format"'
glg='git log --topo-order --graph --pretty=format:"$_git_log_oneline_format"'
```

# Zadatak
Napravit novi branch `nick/account`
stvorit lib/account.rb file
popunit ga sa
```
class Account
end
```
Napravit postojeci file koje ce ljudi editirat da svi editiraju isti file i da vec nesto postoji

* Provjeriti vscode rebase interactive
* Provjeriti intellij rebase interactive

# Stage hunks/lines

# Rebase

# Merge Conflics

# Advanced
* Branch from branch and PRs
* Sign git commits
* Worktree
