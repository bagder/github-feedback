# Better support for PR-by-proxy

We sometimes get patches and proposed changes via other means. Perhaps sent to a mailing list or handed over as a plain pastebin. It's then convenient to help those users by creating a PR for them so that all the CIs, tests and checks etc are performed. PR by proxy. But submitting someone else's patch in a PR still makes GitHub think <strong>I</strong> am the author so I cannot review/approve it! This is especially annoying since git itself properly separates the author from the committer so there's actually info in there that informs about the situation!

