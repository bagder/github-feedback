# Disable the default tarballs for releases

GitHub has a feature that lets you download a tarball of all the files from
any given commit or tag, which is highly useful.

When we do actual releases in the curl project (and other projects as well),
we *generate* a set of files that are included in the shipped (and signed)
tarball. When we make a release, we upload generated tarballs to GitHub to
offer on the "release page". However, GitHub still also always provide two
automatically generated tarballs at the bottom of the list of release
artifacts (one zip, one tar.gz).  Users who against better judgement download
one of those packages from the release page doesn't get a "real" release!

This continues to cause confusions among users.

It would help us to be able to disable them from showing up there.

## Official feedback link

[No way to disable auto-generated source code zip links](https://github.com/github/feedback/discussions/6003)
