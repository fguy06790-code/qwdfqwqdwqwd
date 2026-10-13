# Yren Keys website

Standalone responsive demo license dashboard. Serve this directory with `python3 -m http.server 8001 --bind 127.0.0.1`. Deploy the directory independently to a static host.

Supports duration validation, lifetime presets, Free/Premium/Owner tiers, single key demos, batches of 1–100 one-time code demos, optional PC IDs, copy buttons, and browser-local history. DEMO values do not activate Yren. No private key is included or requested.

Real signing remains blocked by missing yren_common payload/Base32 and code-store/server source. Add a secured authenticated backend with the existing matching signing key held server-side. Never publish a private key. The native client has a compiled localhost redemption URL, so remote redemption requires an appropriate client update.
