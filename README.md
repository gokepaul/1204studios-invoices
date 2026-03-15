# 1204Studios — Invoice System

Internal invoicing, payment tracking, and financial dashboard.

**Live URL:** https://invoices.1204studios.com

## Stack
Pure HTML/CSS/JS — no build step, no dependencies to install.
Data persists via localStorage (browser storage). Upgrade to Supabase for cloud sync.

## Files
- `index.html` — entire application
- `vercel.json` — Vercel routing config

## Deploy
Push to GitHub, import on Vercel, add domain `invoices.1204studios.com`.
DNS: CNAME `invoices` → `cname.vercel-dns.com`

## First-time setup
1. Go to **Settings → Studio Info** — fill in your studio details
2. Go to **Settings → Service Presets** — update prices if needed  
3. Go to **Accounts** — add your real bank account details
4. Go to **Settings → Default Terms** — review and edit your T&C
5. Create your first invoice
