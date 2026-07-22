# HTML5 Player URL (DASH Verification)

Simple single-page DASH player for TV/browser playback verification.

## Default stream
The page is preconfigured to play:

`https://ps-test-vod.cdn.vustreams.com/vizio-poc/dd6a03e2-d526-41c0-b679-7dddb73ad0bd/noscte-nodrm.ism/.mpd`

## Optional URL override
You can override the stream without editing code by appending `?src=`:

`https://<your-pages-url>/?src=https://example.com/stream.mpd`

## Publish with GitHub Pages

1. Go to **Settings** in this repo.
2. Open **Pages**.
3. Under **Build and deployment**:
   - **Source**: Deploy from a branch
   - **Branch**: `main` (or your default branch), folder `/ (root)`
4. Save and wait for deploy.

Your site URL will be:

`https://svenmevissen-xperi.github.io/HTML5-Player-URL/`

## TV verification tips
- Keep **autoplay + muted** enabled for best compatibility.
- Ensure TV has outbound internet access to:
  - GitHub Pages domain
  - Video.js CDN domains
  - Your DASH CDN domain
- If playback fails, test the same URL in desktop Chrome first and check DevTools/network errors.