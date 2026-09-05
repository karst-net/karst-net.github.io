# karst-net.github.io

The public Karst website, served by GitHub Pages from the root of this
repository at <https://karst-net.github.io>.

It is a static site with no build step — edit the files and push.

| Path | What it is |
|---|---|
| `index.html` | The landing page |
| `quickstart.html` | The enrolment quickstart |
| `install.html` | Per-platform install and admin-console configuration steps |
| `styles.css` | All styling for the landing page |
| `assets/` | Logo and mascot artwork |

The admin console ships its own copy of the quickstart at
`web/console/public/docs/quickstart.html`, and the portal ships its own copy of
the install guide at `web/portal/public/docs/install.html`, both in the
[karst](https://github.com/karst-net/karst) repository, which serve them
in-product at `/docs/quickstart.html` and `/docs/install.html` respectively.
Each pair is independent: a change to the wording in one copy should be made in
the other as well.
