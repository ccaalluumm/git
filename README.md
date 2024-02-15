A collection of common but forgettable git scenarios

## Rename branch

Git branch -m <newname>

## Reset to specific prior commit

Git reset —soft <commit ID>

## Interactive rebase with cherry pick on current branch

$ git rebase --interactive 'bbc643cd^'

$ git commit --all --amend --no-edit

## Permanently add ssh key to apple keychain

ssh-add --apple-use-keychain ~/.ssh/id_rsa

## Clone from AWS CodeCommit with SSH

git clone ssh://<SSHKEY-ID>@git-codecommit.<REGION>.amazonaws.com/v1/repos/<REPO-NAME>
