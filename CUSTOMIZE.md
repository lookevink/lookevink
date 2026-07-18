# Customize this profile

The profile is deliberately written so every guess is easy to replace.

## Personal details

- Edit the introduction and “Beyond the code” sections in `README.md`.
- Add LinkedIn, email, or résumé buttons beside the website button.
- Replace `https://loo.ski` if a different personal site should be primary.

## Apple Music listening card

Apple Music does not expose a simple public “now playing” image for profile READMEs. The practical bridge is Last.fm:

1. Create a [Last.fm](https://www.last.fm/join) account.
2. Scrobble Apple Music plays to Last.fm with an Apple Music-compatible scrobbler.
3. Replace `YOUR_LASTFM_USERNAME` below and paste the block into `README.md`.

```html
<p align="center">
  <a href="https://www.last.fm/user/YOUR_LASTFM_USERNAME">
    <img src="https://lastfm-recently-played.vercel.app/api?user=YOUR_LASTFM_USERNAME" alt="Recently played on Apple Music" />
  </a>
</p>
```

## Blog or YouTube feed

The activity workflow currently reads GitHub's public Atom feed. To show posts or videos instead, edit `feed_list` in `.github/workflows/activity.yml`:

- Blog: use the site's RSS or Atom feed URL.
- YouTube: `https://www.youtube.com/feeds/videos.xml?channel_id=YOUR_CHANNEL_ID`

The workflow replaces the content between the `BLOG-POST-LIST` markers in `README.md`.

## Sponsors

GitHub Sponsors is not currently enabled on this account. After enrolling, add a Sponsor button to the contact row and create `.github/FUNDING.yml` if desired.

## Featured repositories

Suggested native profile pins:

1. `whatif`
2. `podio-sdk`
3. `srs-preprocessing`
4. `eso-portal-doc`
5. `embed-gpt-chat`
6. `noah_nc4`
