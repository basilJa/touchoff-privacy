# touchoff-privacy

Public host for the **basilbase privacy policies**, linked from the Google Play listings.

Despite the repository name, this is no longer TouchOff's site alone — it is the single place
every basilbase policy is published. The name is kept because live Play listings point at it.

| App | Live page |
|---|---|
| TouchOff | https://basilja.github.io/touchoff-privacy/ |
| UpTime | https://basilja.github.io/touchoff-privacy/privacy/uptime/ |
| AppLight | https://basilja.github.io/touchoff-privacy/privacy/applight/ |
| RichNotify | https://basilja.github.io/touchoff-privacy/privacy/richnotify/ |

New apps go in `privacy/<slug>/index.html`. Copy the nearest existing page and rewrite the
content: the `<style>` block is shared verbatim so every policy looks like the same product
family. TouchOff's own policy is still the root `index.html` because its published listing
points there; leave it where it is until that listing is changed.

No build step and no Jekyll (`.nojekyll` is present). Edit and push; GitHub Pages redeploys in
about a minute.

Each app's own repository keeps the same text in Markdown (`docs/privacy-policy.md` or
`docs/PRIVACY_POLICY_EN.md`). Keep the two in step, and keep the "Last updated" date current
whenever the policy text changes — Play reviewers check it.

SayIt's policy is still on its own separate repository, `sayit-privacy`, and has not been
migrated here yet.
