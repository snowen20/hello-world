# Hello World

This repo contains a minimal `index.html` Hello World page.

## Run / preview in this container

From `/workspace/hello-world`, run exactly:

```bash
cd /workspace/hello-world
python3 -m http.server 8000 --bind 0.0.0.0
```

Then preview the exact page URL (not just root):

- http://localhost:8000/index.html

Verify it returns the Hello World HTML:

```bash
curl -s http://127.0.0.1:8000/index.html
```

Stop the server with `Ctrl+C`.
