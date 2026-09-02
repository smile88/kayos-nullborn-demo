# KAYOS: Nullborn — playable slices (web demo)

Compiled Godot 4.7 web build. **Build output only — no game source.**

**Play:** https://smile88.github.io/kayos-nullborn-demo/

Two slices, switchable from the menu:

| Slice | State |
|---|---|
| **Festival Town — Bellmoor** | 12 NPCs, three clue sites, the investigation loop |
| **Stonemaw Clan-Hold — ER-01** | Architecture only — nobody lives here yet |

Tap **MENU**, top-left, to switch between them at any time.

**Phone** — left thumb on the left half of the screen walks (gently to walk,
further to stride), right thumb looks, buttons bottom-right are USE, JOURNAL,
CROUCH, HOOD and RUN. Turn the phone sideways.

**Desktop** — WASD, mouse to look, Shift runs, E interacts, J journal, C crouch,
H hood, Esc releases the mouse.

Renderer is `gl_compatibility` — Godot forces this on web — so there is no SDFGI
and no volumetric fog here. The desktop build is Forward+ and looks better.
Capped to 30 fps at 65% render scale on mobile, deliberately: uncapped, a phone
renders ~700 mesh instances flat out until the browser kills the tab.

Delete this repository at any time to take the demo offline.
