# Commit emails with diffs

For better asynchronous and off-line reviews without immediately having to resort to the website. It could use some hueristics and if the diff is too large, skip it.

## Fix it ourselves

This feature *could* be done by ourselves by making a webhook of some sorts that uses the GitHub API, generates the diff and then sends a mail to a dedicated mailing list.
