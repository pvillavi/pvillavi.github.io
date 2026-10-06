# V2 Motion Demo

Experimental motion-enhanced version of the personal site.

- Route: `/v2`
- Source: `src/pages/v2.astro`
- No changes to the production homepage.
- No React runtime added.
- Motion uses vanilla JavaScript, CSS, Canvas, IntersectionObserver, and progressive enhancement.
- Respects `prefers-reduced-motion`.
- Heavy pointer effects are disabled on small screens.

## Motion layers

1. Ambient network canvas.
2. Cursor-reactive blue/violet glow.
3. Restrained portrait parallax on desktop.
4. Terminal-style `PV›_` boot/blink.
5. Scroll reveal for cards and sections.
6. Animated career timeline.
7. Lightweight live-profile telemetry panel.

This branch is intended for visual review before deciding whether any of the effects should move into the production homepage.
