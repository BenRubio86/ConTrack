# ConTrack V1

Files:
- index.html — app
- manifest.webmanifest — Homescreen/PWA metadata
- service-worker.js — offline cache
- icon-192.png / icon-512.png / apple-touch-icon.png — app icons

Deployment:
1. Upload all files in this folder to any HTTPS static host.
2. Open the HTTPS URL in Safari on iPhone.
3. Share → Add to Home Screen → Open as Web App.
4. Open Settings once to set gestational week, maternity-unit phone, local emergency number, and your maternity-unit contact rule.

Privacy:
All contraction/session data is stored locally in browser localStorage. No backend or analytics are included.

Medical scope:
This tracker records timing and patterns only. It does not diagnose labour stage or cervical dilation.
