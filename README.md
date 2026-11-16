# Chinese Chat Time

Independent static website for the Chinese Chat Time podcast. Full Chinese transcripts and pinyin for Episode 01 at HSK 3, 4, 5 and 6; Episode 02 is marked coming soon.

## Cloudflare Pages

Connect this GitHub repository to Cloudflare Pages:
- Production branch: `main`
- Framework preset: None
- Build command: `exit 0`
- Build output directory: `public`
- Root directory: leave blank (repository root)

No API keys, paid dependencies, build tools, or ChatGPT login are needed for this website. Audio listening links go to the Spotify show. All site images, CSS, scripts, and transcripts are local assets.

## Updating content

Edit files under `public/` and commit to `main`. Once Git integration is enabled, Cloudflare Pages publishes new commits automatically. Add a theme card to the homepage when a new episode is ready; do not label incomplete episodes as available.

HSK difficulty is approximate. Conversations are fictional and use AI-generated voices. Pinyin is dictionary-based support.
