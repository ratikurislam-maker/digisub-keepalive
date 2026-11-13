# DigiSub Hub keep-alive

Pings https://digisub-hub.onrender.com/api/health every 10 minutes so the
site stays awake on Render's free plan (which sleeps after 15 minutes idle).

Public on purpose: GitHub Actions minutes are unlimited for public repos.
Nothing sensitive lives here — the workflow only curls a public URL.
