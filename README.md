# subtree-parakeet

## Commands run

### Setup
`git subtree add --prefix=shared-subtree <turbo-parakeet-url> main --squash`

### Changing from this repo
`cd shared-subtree/shared-subtree`

Change code

`git commit -m "Update subtree from subtree-parakeet`

`git subtree push --prefix=shared-subtree <url> main --squash`

### Pulling changes

`git subtree pull --prefix=shared-subtree <url> main --squash`
