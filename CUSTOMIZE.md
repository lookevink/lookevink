# Customize this profile

The profile is deliberately written so every guess is easy to replace.

## Personal details

- Edit the introduction and “Beyond the code” sections in `README.md`.
- Add LinkedIn, email, or résumé buttons beside the website button.
- Replace `https://loo.ski` if a different personal site should be primary.

## Spotify now playing

1. Authorize your Spotify account at [spotify-github-profile](https://spotify-github-profile.kittinanx.com/api/login).
2. Copy the generated card URL.
3. Replace `YOUR_SPOTIFY_UID` below and paste the block into `README.md`.

```html
<p align="center">
  <a href="https://open.spotify.com/user/YOUR_SPOTIFY_UID">
    <img src="https://spotify-github-profile.kittinanx.com/api/view?uid=YOUR_SPOTIFY_UID&cover_image=true&theme=default&show_offline=false&background_color=0d1117&interchange=false" alt="Spotify now playing" />
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
