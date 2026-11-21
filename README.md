# ANOCATCH TZA 🇹🇿 — MOVIE & CONNECTION

Responsive video catalog and starter admin dashboard using Supabase.

## Setup
1. Run `supabase/schema.sql` in Supabase SQL Editor.
2. Enable Google provider in Supabase Authentication and configure Google OAuth credentials and redirect URLs.
3. Add the deployed website URL to Supabase Authentication URL Configuration.
4. Copy the Supabase Project URL and anon/public key from Project Settings > API into `SUPABASE_URL` and `SUPABASE_ANON_KEY` in `app.js`. Never use the `service_role` key in browser code.
5. Deploy this repository with Cloudflare Pages using Git integration. Framework preset: None; build command blank; output directory `/`.
6. Sign in using Google as `destinyline0000@gmail.com`. Database policies restrict writes to that email.

## Video links
Admin may add direct HTTPS video URLs they own or are authorized to distribute. A Google Drive sharing page is not automatically a direct playable video URL. Do not bypass DRM or access restrictions.

## Payments
Paid listings currently show a WhatsApp request link for manual payment coordination at TSh 500. This is not an automated payment gateway, does not verify payment, and does not securely unlock paid content. Add a payment provider with server-side verification before accepting payments.

## Storage
This starter stores video URLs, not movie files. Use a video/storage service designed for large files and streaming; the website host is not intended for movie hosting.
