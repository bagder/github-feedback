# A "merges" keyword

It could work similar to the magic `closes #NNN` and `fixes #NNN` keywords when a commit is pushed. To enable later searching for pull-requests (PRs) that were merged/not merged - and the PR could also possibly mention which branch it went into. Since we almost always edit and merge PRs directly in git, without using GitHub, virtually all PRs are just "closed by [commit]" when viewed on GitHub. Which isn't ideal, as they can also be closed for other reasons. Users are also often confused when their pull-requests are marked "closed" and not "merged" when they in fact were merged.

This has recently caused some friction when working with hacktoberfest, who won't consider pull-requests that are closed with the `closed` keyword as merged.

## Official feedback link

[Marking pull requests as merged](https://github.com/github/feedback/discussions/6414)
