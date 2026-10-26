Hermit's lockdown engine, published in full.

Most focus apps tell you they don't spy on you. We show you instead. This is the actual code that enforces a Hermit session — what it watches, what it blocks, and what it never does.

What it does:
- Blocks apps, sites, and windows you mark as off-limits for the duration of a session
- Locks itself in — the app can't quit itself mid-session
- Survives crashes, reboots, and restart attempts (session state is restored)

What it never does:
- No logging of what you were doing before a blocked attempt
- No recording of keystrokes, screens, or tabs
- No telemetry, no analytics, no network calls beyond [X — fill in]
- No escalation: it blocks, it reports that a block happened, that's the end of it
Audit it. It's all here.
