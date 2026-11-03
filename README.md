# D R . F R O G M A N — VTuber Page 🐸🪷

A single-file, deliberately busted 2000s-style VTuber site for **Dr. Frogman**, set in a night swamp full of lily pads.

- **The frog:** a lanky, side-on frog in the style of Dat Boi, with a white sticker outline. He stands on a lily pad (no unicycle) and snaps between two dab poses like stop-motion. Poke him for a croak, a hitmarker and an emote burst. Every 5th poke plays an airhorn and drops "deal with it" shades on him.
- **Emote Pond:** 14 original tribute frog emotes (FeelsGoodMan, monkaS, PepeHands, COPIUM, Madge, Deadge, EZ, Pepega and more). Click one to copy its name.
- **Meme effects:** the page is deep-fried by default (button cycles fried → nuclear → clean). Every click leaves an MLG hitmarker and pops up text like "+100". Meme stickers (BASED, RATIO, SKILL ISSUE…) are slapped on every section. Also: a fake stream chat that spams emotes, Win98 error popups with a dodging OK button, a marquee and hazard tape.

## Customize
Everything lives in `index.html`.

- **Live badge, schedule, timezone:** edit the `CONFIG` block at the top of the `<script>`. Visitors see stream times converted to their own local time.
- **Social links:** search for `✏️ Replace each href="#"` and paste your Twitch / YouTube / Steam / Discord / socials URLs.
- **Text and lore:** edit the About, Streams and Lore sections directly.
- **Chat messages / emotes:** edit the `CHAT` and `USERS` arrays. Write `:EmoteName:` in any message to show that emote.

## Host it free with GitHub Pages
Repo → **Settings → Pages** → Source: *Deploy from a branch* → pick the branch and `/ (root)` → Save.
