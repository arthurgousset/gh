# Github CLI (`gh`)

Source: [`gh` docs](https://cli.github.com/manual/gh)

## Open repo in browser

```zsh
gh browse .
# or
gh repo view --web
```

Source:
[Github Gist](https://gist.github.com/igrigorik/6666860?permalink_comment_id=4187534#gistcomment-4187534)

## Open PR associated with local branch

```sh
$ gh pr view --web
```

## Trigger workflow

You can trigger Github workflows from the command line like
[here](https://github.com/celo-org/celo-monorepo/actions/runs/9695682075).

```sh
$ gh workflow run "Protocol Devchain Anvil" --ref soloseng/governance-hotfix -f npm_tag=governance-hotfix
```

Source: [Leszek on Slack](https://clabsco.slack.com/archives/C0484DDLW5B/p1719487491834429)
