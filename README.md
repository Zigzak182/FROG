# D R . F R O G M A N — VTuber Page 🐸🪷

A single-file, deliberately busted 2000s-style VTuber site for **Dr. Frogman**, set in a night swamp full of lily pads.

- **The frog:** a hand-drawn, upright waving frog with jittery "boiling" lines, a head mirror and a stethoscope. He stands on a lily pad (no unicycle). One eye follows your cursor and the other goes the wrong way. Poke him for a croak, a speech bubble and an emote burst.
- **Emote Pond:** 13 original frog emotes drawn as tributes to classic frog emotes (FeelsGoodMan, monkaS, PepeHands, COPIUM, and more). Click one to copy its name.
- **The junk:** a fake stream chat that spams emotes, Win98 title bar and error popups (the OK button dodges you), a marquee, hazard tape, a deep-fry button, a fly cursor trail, a visitor hit counter, and a Sadge frog that peeks in from the corner.

## Customize
Everything lives in `index.html`.

- **Live badge, schedule, timezone:** edit the `CONFIG` block at the top of the `<script>`. Visitors see stream times converted to their own local time.
- **Social links:** search for `✏️ Replace each href="#"` and paste your Twitch / YouTube / Steam / Discord / socials URLs.
- **Text and lore:** edit the About, Streams and Lore sections directly.
- **Chat messages / emotes:** edit the `CHAT` and `USERS` arrays. Write `:EmoteName:` in any message to show that emote.

## Host it free with GitHub Pages
Repo → **Settings → Pages** → Source: *Deploy from a branch* → pick the branch and `/ (root)` → Save.
