# AI Role Mapper

A free, browser-based tool built for marketing and communications roles. Paste a job description and see its responsibilities sorted three ways:

1. **AI can largely handle it.** Pattern-based work with established formats: monitoring, routine reporting, templated drafts, repurposing, workflow operations.
2. **AI assists, human drives.** Work where AI speeds things up but a human owns the framing, accuracy, or the call: high-stakes writing, strategy, translating complexity, crisis support.
3. **Human required.** Trust, relationships, live judgment, leading people, being the accountable face. AI can prep you for these moments; it cannot be in them.

Try it: open `index.html` in any browser, or visit the hosted version via GitHub Pages.

## What makes it different

Most "will AI take my job" tools hand you a scary percentage. This one refuses to, because jobs are not task lists. Instead it shows where AI buys you hours back and where the human parts of your work are the whole point. A few design choices worth knowing about:

- **Built from 75 real job descriptions.** Entry-level to C-suite, in-house and agency, across PR, internal comms, brand, product marketing, growth, marketing ops, executive comms, and policy comms. Every rule in the engine was tested against real postings, not invented in the abstract. One finding held across all 75 without a single exception: relationship building stayed human.
- **Context changes the answer.** The same task lands in different buckets depending on stakes. Regulated industries (healthcare, finance, legal, government, defense) shift work toward human review, and classified or clearance environments can rule out AI tools entirely. The tool detects these contexts, or you can set them manually.
- **Career-stage awareness.** Entry-level desk roles are the most automatable in the corpus, and they're also where people build the judgment senior roles require. The tool flags "keep your reps" tasks for early-career users and gives leaders a note about protecting the training ground, because if AI absorbs all the junior reps, nobody develops into your next senior hire.
- **Direction of travel.** Each verdict is marked stable or shifting, because bucket assignments drift as AI improves. Bucket two is a place to build leverage, not a place to hide.
- **Honest about its limits.** It's rules-based pattern matching that runs entirely in your browser. Nothing you paste is stored or sent anywhere. When a JD gives it too little to work with, it says so instead of faking confidence.

## Deploying on GitHub Pages

1. Fork or clone this repo.
2. In the repo settings, go to Pages and set the source to the main branch, root folder.
3. Your copy will be live at `https://<your-username>.github.io/<repo-name>/`.

No build step, no dependencies, no backend. It's one HTML file.

## The framework

The full rulebook (31 rules, 3 context modifiers, and the design observations behind them) lives in [`FRAMEWORK.md`](FRAMEWORK.md). Corrections and additions are welcome; open an issue with the job description that broke a rule.

## Roadmap

- v2 (maybe): an optional AI-powered analysis mode for JDs the pattern matcher reads poorly. The rules-based version will always remain the free default.

## Credit

Built by [Austley](https://austley.com) from 75 real marketing and communications job descriptions. Released as a community resource.

## License

MIT
