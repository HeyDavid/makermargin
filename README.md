# Maker Margin

Custom Astro landing page for `makermargin.co`.

Beehiiv remains the email backend and automation system. This site owns the public brand surface and embeds the Beehiiv subscribe form.

## Commands

Use the workspace npm runtime directly if the global npm shim is broken:

```powershell
& 'D:\node.exe' 'D:\node_modules\npm\bin\npm-cli.js' install
$env:ASTRO_TELEMETRY_DISABLED='1'; & 'D:\node.exe' 'D:\node_modules\npm\bin\npm-cli.js' run build
```

Standard commands also work when npm is healthy:

```sh
npm install
npm run build
npm run dev
```

## Notes

- Built with Astro + Tailwind via `@tailwindcss/vite`.
- Deployed to Vercel.
- Primary CTA points to the Etsy listing.
- Subscribe form uses Beehiiv iframe embed.
