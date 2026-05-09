# 🎧 Hey DJ

> *"vibe in, music out"*

A personal DJ agent built with [OpenClaw](https://openclaw.ai) that actually knows your taste — not just what you played last week.

## What it does

Tell it how you're feeling. Get music back.

```
"rainy sunday morning, slow, introspective"
→ playlist: soft launch of the day

"pre-workout, building energy, beat and rhythm"  
→ playlist: slow burn saturday 🌅
```

## How it's different from Spotify/SoundCloud recs

- Knows your **full musical DNA** — not just your recent plays
- Understands the **underground circuit** you follow (Domply, Gop Tun, Kala, Houghton...)
- Finds the **Brazilian × electronic intersection** the algorithm never touches
- Surfaces songs you **forgot you loved**
- Doesn't over-index on your location (bye, Brazilian music bias)

## Built from

- 🎵 Spotify listening history (top artists, tracks, recently played)
- 🎶 SoundCloud likes (87 tracks — the real you)
- 🎫 2 years of event tickets (54 parties across SP, RJ, Salvador, Madrid, Barcelona, Albania, Croatia, London)
- 🧠 Scene knowledge base (SP/RJ underground, European festival circuit, key artists)

## Files

- `agents/dj/SOUL.md` — the DJ agent's personality and rules
- `agents/dj/taste_profile.md` — full musical DNA
- `agents/dj/scene_knowledge.md` — knowledge base: parties, DJs, festivals
- `agents/dj/event_history.json` — 54 events from the last 2 years
- `agents/dj/soundcloud_likes.json` — 87 SoundCloud likes

## Stack

- [OpenClaw](https://openclaw.ai) — agent runtime
- Spotify API — playlist creation + history
- SoundCloud API — likes + follows
- GitHub — version control for the agent brain

---

*Built on a Saturday morning while vibe coding 🌅*
