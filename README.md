# mirrorbot-workflow

You can use [this repo](https://github.com/lzzy12/python-aria-mirror-bot) as a template

First setup everything then push to your private Repository

Then Fork this Repo

Setup secrets in settings --> Secrets

```text
GH_TOKEN :- Your github personal access token, from https://github.com/settings/tokens
MIRROR_REPOSLUG :- Your Secret Repository, as in "<username>/<reponame>"
```

Then edit .github/workflows/*.yml

Change `GitHubMail` and `GitHubName` environment variable as your own

And That's it.

©ElytrA8
