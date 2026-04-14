# xss-share

Password-protected one-pagers for the Xssentials team.

Each folder contains a single `index.html` encrypted with [StaticCrypt](https://github.com/robinmoisson/staticrypt). Open the URL, enter the password you were sent, and the content renders locally in your browser.

## For viewers

You'll get a link like `https://bgjameson.github.io/xss-share/<item>/` and a password, usually in the same message. Paste the password, hit Enter, done.

## For the maintainer

See the publishing workflow in the Coppermind vault: `02_Library/Reference/github-publishing.md`.

Rules of the road:
- Only encrypted output lives here. Source HTML stays in the vault.
- No passwords in this repo, ever. Track them privately.
- No client-identifiable folder names without consent — use opaque slugs.
