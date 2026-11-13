# DigiSub Hub keep-alive

Pings https://digisub-hub.onrender.com/api/health every 10 minutes so the
site stays awake on Render's free plan (which sleeps after 15 minutes idle).

Public on purpose: GitHub Actions minutes are unlimited for public repos.
Nothing sensitive lives here — the workflow only curls a public URL.

Status: live since 2026-11-13. A manual run succeeded the same day; the
scheduled runs are monitored — if GitHub's scheduler ever stalls, a new
commit to this repo re-syncs it.
