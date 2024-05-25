# Mark specific users as suspicious

GitHub has some controls to limit when CI jobs can start for users, but they
are not fine-grained enough.

It would be super helpful if a maintainer could mark a user as "suspicious" to
specifically make that user's pull-requests up for review and approval before
they run (again). Would be applied when a PR that looks strange or weird is
pushed.

Ideally, such a "mark" would also allow a maintainer to desrcibe the descision
with a comment that only is visible to other project maintainers - not for the
public.
