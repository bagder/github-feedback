# A "merges" keyword

It could work similar to the magic `closes #NNN` and `fixes #NNN` keywords when a commit is pushed. To enable later searching for pull-requests (PRs) that were merged/not merged - and the PR could also possibly mention which branch it went into. Since we almost always edit and merge PRs directly in git, without using GitHub, virtually all PRs are just "closed by [commit]" when viewed on GitHub. Which isn't ideal, as they can also be closed for other reasons. Users are also often confused when their pull-requests are marked "closed" and not "merged" when they in fact were merged.

## Hacktoberfest

This has previously caused friction when working with hacktoberfest, who won't consider pull-requests that are closed with the `closed` keyword as merged.

## Pull Shark badge

As a direct result of GitHub not being able to properly track or understand
merges that are done outside of GitHub's own tooling, new fancy things such as the achivement badges experimented with ("beta" status) during summer of 2022 with its **Pull Shark** gets it wrong too.

The **Pull Shark** badge supposedly shows a `x2`, `x3`, `x4` etc label on the little icon depending on the number of merged pull requests you have had registered in total.

But if you have had thousands of Pull Requests merged "manually" with the `Closes` keyword, they are not included in that count.

## Official feedback link

[Marking pull requests as merged](https://github.com/github/feedback/discussions/6414)

The oldest request found for this feature is from [June 2013 on isaacs/github](https://github.com/isaacs/github/issues/2).
