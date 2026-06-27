# Jackfish

Jackfish is a single-page 3D tank simulation inspired by Jackfish storm movement, boids, color spread, food ecology, and a first-person playable fish view.

## Run Locally

```bash
python3 -m http.server 8765 --bind 127.0.0.1 --directory outputs
```

Open:

```text
http://127.0.0.1:8765/Jackfish/index.html
```

Moai inspection mode:

```text
http://127.0.0.1:8765/Jackfish/index.html?debug=moai
```

## Cloudflare Pages

Use `outputs/Jackfish` as the Pages build output directory. The app is static and does not need a build command.
