# propercourse-site

The public website for [Proper Course](https://propercourse.app/), served by
GitHub Pages. Plain HTML and CSS with no build step: edit a file, push to
`main`, and Pages publishes it within a minute or two.

- `index.html` — home page
- `privacy.html` — privacy policy (the App Store Connect listing links here)
- `style.css` — shared styles; fonts come from Google Fonts
- `images/` — banner photo, app icon, screenshot
- `join/index.html` — shown for invitation links (`/join#<token>`) when the app isn't installed
- `.well-known/apple-app-site-association` — lets iOS open `/join` links in the app (served thanks to `.nojekyll`)

Preview by opening `index.html` in a browser; all links are relative.

The Proper Course API is served separately, at `api.propercourse.app`.
