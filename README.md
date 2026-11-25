# prefill.here

The home page for Prefill, at **https://prefill.here**. Prefill works on AI engineering, mostly how to run models fast and cheap. The notebook lives at [learn.prefill.here](https://learn.prefill.here) ([source](https://github.com/sahil0x01/prefill-learn)).

Plain HTML and CSS in `public/`, no build step. Served as static assets by a Cloudflare Worker (`prefill-home`). It uses the same visual system as Learn.

```bash
npm install      # once
npm run dev      # http://localhost:8787
npm run deploy   # upload to Cloudflare (run `npx wrangler login` once first)
```

Fonts (Geist, Geist Mono, EB Garamond) are self-hosted from `public/fonts/` under the SIL Open Font License.

Code is [MIT](LICENSE).
