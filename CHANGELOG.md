# Changelog

## 1.0.5 — 2026-11-17

Brings Spray in line with the JAS.BLACK tool family's shared interface rules.

- **One purple:** the interface violet (readouts, the colour code, the images / build mode pill, focus rings) is now `#8b6cff`, as in every family tool. Paint colours are unchanged.
- **Right-click resets any setting** to how it was when the page loaded: sliders, the colour fields, the cap or marker, the mode switch, spray can / marker, paint / buff, the guide, auto paint, aim ring and sound chips, and the light. Action buttons keep the normal menu; right-drag on the 3D view still looks around.
- **Dot grid:** the background dots are a fixed tile now, finer and fainter (16 px spacing), dark and light. They were a live CSS gradient, which can shimmer on macOS.
- **Key bar:** the strip under the yard lists the main keys as small raised keys, each with one word, ending with "right-click a setting resets it". Hidden on touch screens.
- The unused numbered-step badge style is gone (Spray has no easy mode).

## 1.0.4 — 2026-11-17

- New starting setup: **NY Fat** cap, **13.5 cm** distance, **90%** pressure, light drips, **Lemon** paint.

## 1.0.3 — 2026-11-17

- Image guides no longer show the colour numbers by default: you get the outlines and colour fills. Turn **Numbers** on in the Images tab for any image that needs them. Yards and project files saved earlier keep their own setting.

## 1.0.2 — 2026-11-17

- Works on phones and tablets. Below 900px wide the top bar becomes a row of icon keys (undo, back to wall, redo, rec, tools, full screen, theme) with the paint · images · build switch on its own row underneath, so nothing overlaps.
- On phones the tools open as a sheet under the 3D view; the tools key lights up while it is open. The floating tools button, key hints and monitor caption are hidden on small screens.
- Phones held sideways keep a single top bar and put the tools beside the view.
- Bigger touch targets: taller keys and chips, larger slider knobs.
- Respects the iPhone notch and home bar, and sizes to the visible screen (no jump when the browser bar hides).
- The full-screen key is hidden where the browser can't go full screen (iPhone Safari).

## 1.0.1 — 2026-11-12

- Renamed from Spraylab to **Spray**: the title, tab, link preview, home-screen name, messages and exported file names (`spray-recording…`, `spray-photo.png`, `spray-wall.png`, `spray-project.json`).
- Saved settings, the autosaved yard and project files from Spraylab keep working: their internal names (`spraylab-ui`, the `spraylab` browser store, `app: 'spraylab'` in project files) are unchanged on purpose.

## 1.0.0 — 2026-11-12

First public release at [spray.jas.black](https://spray.jas.black).

- New console layout in the JAS.BLACK style: top bar with mode switch, status lights and transport keys, a docked tool panel, and the yard in a framed monitor with a status strip.
- Light and dark themes (◐), remembered between visits. Full-screen key.
- Hiding the tools (H) gives the 3D view the whole width.
- The hand-tracking light shows when the camera is on.
- Live multi-user painting is only offered where it works (inside a shared Claude artifact), so it is hidden on the website.
