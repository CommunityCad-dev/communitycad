# CommunityCAD

**[communitycad.dev](https://communitycad.dev)** is a free place to find, share and print open hardware designs.

This repository is CommunityCAD's **public roadmap and feedback tracker**. It has no code in it. Use it to:

- see what's planned, being built and recently shipped
- report a bug or ask for a feature
- follow what happens to your request

## How to send feedback

The easiest way is the **Feedback** button on communitycad.dev. What you send there (bug reports, feature requests and general feedback) is posted here as a public issue automatically, so please don't include anything private. Messages sent through the **Contact** form stay private and never appear here.

You can also open an issue here directly.

On the site you can **vote on feature requests**. Votes help decide what gets built next.

## Labels

| Label | Meaning |
|---|---|
| `bug` | Something on the site doesn't work as it should |
| `feature` | A request for something new |
| `feedback` | General feedback |
| `unreviewed` | New and not looked at yet |
| `planned` | We intend to build it |
| `in progress` | Being built now |
| `shipped` | Live on communitycad.dev |

## Why the website's code isn't here

The CommunityCAD website and service are not open source. The tools that bring CommunityCAD into other apps are. In short:

- **There's nothing new in the website.** It's an ordinary web service: a frontend, a backend, a couple of databases and some background workers. Plenty of open-source file-sharing sites already exist, so publishing ours wouldn't give anyone a technique or tool they don't already have.
- **It's built and run by one developer.** Keeping it closed means that time goes into the site itself, not into running an open project around it.
- **What adds something new to tools people already use is open.** [Hopper](https://github.com/CommunityCad-dev/Hopper), the Klipper printer plugin, is GPL v3 or later, and the [CommunityCAD MCP server](https://github.com/CommunityCad-dev/communitycad-mcp) for AI apps is Apache 2.0. Anyone can read them, check what they send, improve them or reuse them.
- **Your work isn't locked in.** You keep ownership of your models and choose their license, your GitHub repo can stay the source of truth, and public models stay free to download.

The full explanation, including how creators get paid, is in the docs: **[Why CommunityCAD isn't open source](https://communitycad.dev/docs/communitycad/open-source)**.

Being closed source is exactly why this tracker is public: you can see what we're working on and tell us what you need.
