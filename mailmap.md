# Respect .mailmap

git supports a `.mailmap` file that a project (like curl) can edit to update
user information after the fact. It can also be used to mark how two different
users (email addresses) is actually the same user.

The GitHub contributor counter doesn't seem to respect this file, which makes
some contributors that changed email address over the years, to not have all
their contributions counted when listed in the "contributors" view for a
repository.

## Official feedback link

[Respect git .mailmap](https://github.com/github/feedback/discussions/6754)
