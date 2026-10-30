# maine-news-keepalive

Pings the Maine news agent's `/ping` endpoint every 5 minutes so the free Render service never
sleeps. `/ping` does not touch the database, so Neon still autosuspends when idle.
