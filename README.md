# touchoff-privacy

Public host for the TouchOff privacy policy, linked from the Google Play listing.

**Live page:** https://basilja.github.io/touchoff-privacy/

`index.html` is the whole site — a single self-contained page, no build step and no Jekyll
(`.nojekyll` is present). Edit it and push; GitHub Pages redeploys in about a minute.

The app itself lives in a separate private repository, `TouchOff`, whose
`docs/PRIVACY_POLICY_EN.md` holds the same text in Markdown. Keep the two in step, and keep
the "Last updated" date in `index.html` current whenever the policy text changes — Play
reviewers check it.
