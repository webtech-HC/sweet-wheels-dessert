# Sweet Wheels — Desserts on the Go!

A pastel, high-converting landing page with a “Spin to Win” discount wheel.

- **Design:** V3 “Pastel Ultra” (glassy nav, soft gradient blobs)
- **Wheel:** Top Font Awesome pointer, deterministic landing
- **Tech:** Plain HTML/CSS/JS + CDN assets (no build tools)

## Preview

Enable **GitHub Pages** (Settings → Pages → Source: “GitHub Actions”) and push to `main`. The included workflow deploys automatically.

## Customize

- Replace placeholder images (search for `placehold.co`).
- Edit copy in hero / value tiles / menu / booking form.
- Spinner labels and weights live inside `<script>` near the bottom.

## Spinner Notes

- Pointer is **at the top** (CSS 270°).
- Wheel lands with the chosen slice **centered under the pointer**.
- Change pointer side by modifying `POINTER_CSS` (0=right, 90=bottom, 180=left, 270=top).

## Local dev

Just open `index.html` in a browser. If using VS Code, the “Live Server” extension works great.

## License

MIT — see `LICENSE`.

