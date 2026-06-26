# Sentivel docs: voice and style

Write like a senior engineer explaining to a peer. Never like AI. This is the bar
every page is reviewed against (Linear COR-488). It matches the voice of the docs
we admire (Better Stack and Stripe), plus the Sentivel house rules.

## Voice

- **Second person, imperative.** Instruct, don't narrate. "Add a monitor." Not
  "You can add a monitor" or "This guide will show you how to add a monitor."
- **Short, declarative sentences (~8–15 words).** One idea per sentence. Active
  voice. Every sentence earns its place.
- **Context, then action.** One line of what or why, then the steps. No preamble.
  Don't restate the heading in the first sentence.
- **Task-based headings**, gerund or imperative ("Add a monitor", "Publish a
  status page"). Never "Overview", "Configuration", or Title Case Everything.
- **Numbered steps** for sequences. Each step is one action plus its expected
  result ("You get back the workspace, the token's role, and its capabilities").
- **Real, runnable code**, labelled by language or file. Show the actual response.
  Never "here's an example:".
- **Define a term inline**, in parentheses, the first time it appears.
- **Callouts state a fact** (`<Note>`), used sparingly. No "Warning:!" shouting.
- **Link text names the destination** ("the API reference"). Never "click here",
  "this page", or "for more information, see…".

## Banned: the AI tells. Never ship these.

- **Hype:** powerful, robust, seamless, effortless, blazing-fast, cutting-edge,
  world-class, comprehensive, rich, elegant, delightful, magical, supercharge,
  unlock, elevate, leverage, harness, empower, game-changing.
- **Filler openers:** "In today's fast-paced world", "When it comes to", "It's
  worth noting that", "Needless to say", "At its core", "Simply put", "Let's dive
  in".
- **Hedging / conditional fluff:** easily, simply, just, "feel free to", "you
  might want to", "you can simply", "as you may know", "optionally consider".
- **LLM tells:** delve, tapestry, realm, "navigate the landscape", "in
  conclusion", Furthermore/Moreover chains, emoji as punctuation, em dashes,
  over-bulleting, empty transitions, padding.

## Process

Draft, then read it aloud. Cut every word that doesn't change the meaning. Check
it against the banned list. Ask: does this sound like a person who built the
thing, or a marketing bot? `quickstart.mdx` is the on-voice reference.
