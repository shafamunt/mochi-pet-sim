# Mochi the Cat

A cute virtual pet cat simulator game. One self-contained HTML file, no build step, no external dependencies.

Mochi is a virtual cat you care for over time. Pet her by dragging or tapping, feed her meals, play a tap-the-mouse mini game, and dress her up in the wardrobe. Hunger and happiness decay in real time (tracked via localStorage timestamps), so she keeps living even when the tab is closed.

## How to run it locally

Just open `mochi.html` in any modern browser (double click it, or serve the folder with `python3 -m http.server` and visit the shown address). It works well on a phone screen.

## Features

- Renameable cat (default name: Mochi)
- Two breeds: Lynx Point Siamese (default) or Ragdoll, drawn in inline SVG. Breed is chosen on first visit and changeable in Settings.
- Petting: drag or tap the cat. Hearts float up, a "Purrr..." bubble appears, happiness rises.
- Feed and Play buttons. Play starts a 15 second tap-the-moving-mouse mini game.
- Hunger and happiness meters decay over real time via localStorage timestamps. Feeding restores hunger; petting and playing restore happiness. At zero hunger Mochi looks sad and the status text asks for food.
- Wardrobe tab with 3 outfits drawn as SVG overlays: pink dress with a bow, blue sailor outfit, cozy sweater. Choice persists.
- Cute status messages, blinking eyes, breathing animation, and a sad face with a tear when very hungry.

## File layout

- `mochi.html` - the whole game: HTML, CSS, and JS are all inline in this one file.

## Continuing this work

Another AI picking this up: all game source lives in `mochi.html` (markup, styles, and the game script are inline, no build step). Edit that file directly, open it in a browser to test, and hand the finished result back to Shafayet's Muse so it can rebuild and redeploy the hosted artifact.

Hosted artifact slug: `mochi-the-cat` (web_static). Open and share it from its artifact card in Muse.
