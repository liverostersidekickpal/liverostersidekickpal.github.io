LIVE ROSTER: copy-ready name lists from your Planning Center check-ins

These are the files for the Live Roster website. Upload all of them to a
GitHub repository with GitHub Pages turned on. Keep them together; the
page needs every file.

  index.html             the app (people sign in with Planning Center;
                         its public Client ID is set near "CLIENT_ID")
  guide.html             shareable setup guide (…/guide.html)
  manifest.webmanifest   lets browsers install it as an app
  sw.js                  lets it open quickly and install in Chrome/Edge
  icon.svg, icon-*.png, apple-touch-icon.png   the app icon

To update everyone's app later, upload a new index.html to the same
repository. Installed copies pick it up the next time they open.
