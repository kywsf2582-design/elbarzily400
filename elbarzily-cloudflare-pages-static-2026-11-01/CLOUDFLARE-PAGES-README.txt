El Barzily - Cloudflare Pages Static Export

Upload the contents of this folder to Cloudflare Pages using Direct Upload,
or set the Pages build output directory to this folder when using a Git build.

SPA routing is enabled by _redirects.

Important limitation:
This is the compiled frontend only. It does not include the Node/Express API,
MySQL/Neon database, authentication/OTP server, bookings API, chat API, SSE,
or Web Push server. Those features need a separately deployed compatible backend.
The generated /api/platform/config.js contains public browser configuration only.

For a Git-based Pages deployment, use:
- Build command: pnpm build:static
- Build output directory: dist/public

For this ZIP, upload the files in this folder directly as the Pages asset root.
