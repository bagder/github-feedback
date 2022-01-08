# Mark specific CI builds flaky

If there was an ability to mark individual CI failures as "temporary
unreliable don't count them and still consider the full change green"
(possibly "because of X") or similar, this would greatly help in particular
newcomers who may be very perplexed and confused about the failing CI builds
that seem and are totally unrelated to their particular change! Flaky CI
builds are a complicated issue.

Sometimes a particular CI goes bad and we know it will remain bad for a while.
We subsmit an issue and want to fix it. It would be awesome to then be able to
link/explain coming CI job failures for that job to link to the issue for that
particular case.
