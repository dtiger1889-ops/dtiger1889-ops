# D.M.

I have always tried to streamline any task I have to do more than once. I'm not a developer, but coding agents turned that habit into the projects below. Almost all of them started with something in my own day that was slow or easy to forget, and I kept going long after a reasonable person would have stopped.

## Projects

- **[Claude Code Harness Toolbox](https://github.com/dtiger1889-ops/claude-harness-toolbox).** Coding agents forget the whole project every time the context resets, and I got tired of explaining everything again. This is the harness I built around them: orientation rules, short checkpoint files, hooks, and skills that carry a project from one session to the next.

- **[Hintforge](https://github.com/hintforge/builder).** I wanted help with games without getting spoiled or scrolling through an ad-covered wiki for one answer. Hintforge is a hint companion that knows where you are in the game, only answers what you ask, and remembers your progress.

- **[Life OS](https://github.com/dtiger1889-ops/life-os).** My life admin was spread across a dozen cloud apps that own the data and stop working offline. Life OS keeps it in one SQLite database on my own PC, with an offline-first Android app, browser dashboards, and an agent on top. It also comes with a playbook for adding a new area of life in an afternoon.

- **[Concur Buddy](https://github.com/dtiger1889-ops/concur-buddy-app).** Concur is slow enough that I wait and file my expenses all at once, and by then the details are gone. Concur Buddy is a local Windows app where logging an expense takes one field, and when it's time to finish the report it pulls in the card charges Concur added and merges them with what I already logged.

- **[whatdoweplay](https://github.com/dtiger1889-ops/whatdoweplay).** Steam sales tell me what's cheap, and I wanted something that tells me what I'll actually play. It scores sales, giveaways, and my backlog against a taste model built from real playtime. The friends-night picker came later, because a group on Discord can lose an hour deciding what to play, and it only offers games everyone in the call already owns.

- **[Obsidian Integration](https://github.com/dtiger1889-ops/obsidian-agent-integration).** A second brain turns into another inbox unless something keeps it organized. This is the setup I use for capturing notes from my phone, letting an agent file them, approval gates, and project memory that lasts between sessions.

## How I build

- Personal data stays local. Privacy should come from how the thing is built, not from a promise in the footer.
- If a tool claims to help, I want a test, a counter, or an audit trail that shows it.
- I build for the tired version of the user, the one who is distracted or already annoyed.
- I care more about something surviving the next session and the next mistake than about it working once in a demo.
