# papers-sync site

Static app information and privacy policy for the personal papers-sync Google Drive utility.

Publish only these website files using GitHub Pages. No credentials or Drive documents belong in this source directory.

- `index.html`: application home page
- `privacy.html`: privacy policy
- `styles.css`: shared responsive styles
- `.nojekyll`: serve the static site without Jekyll

For branch publishing, select the branch containing these files and `/(root)` in Settings → Pages. If the files are placed under `docs/`, select `/docs` instead. The actual homepage URL is shown in Settings → Pages after deployment; the privacy policy is `privacy.html` relative to it.

In Google Auth Platform → Branding, use the live home page and privacy policy URLs. Add the site host to Authorized domains if required by the console. Then revisit Audience to publish the app. This website does not itself change the OAuth publishing status or eliminate Google's verification requirements.
