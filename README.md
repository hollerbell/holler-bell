# Holler Bell

**All your agents. One window.**

Holler Bell is a desktop app for Claude Code, Codex, shells and SSH. When an agent finishes and waits for you, Holler Bell shows you which session it is.

**[Download for Windows, macOS and Linux](https://hollerbell.com/?ref=github#download)**

Free, at home and at work. No account and no license key.

## What it does

- **Every session, grouped by folder.** Sessions sit under the folder they run in. SSH sessions show the host they're connected to.
- **See who's waiting.** The row turns amber and a notification names the session. Working sessions stay quiet.
- **Resume after a restart.** "Resume all" brings your sessions back. Agents continue their conversations and SSH sessions in tmux reconnect. Plain shells start fresh.
- **Views.** Put the sessions for a task side by side and switch between views with a click.
- **Waiting queue.** Click the waiting count to jump to the session that has waited longest.

Runs on Windows, macOS 12 Monterey or later, and Linux.

To run agents, install Claude Code or the Codex CLI and make sure it's on your PATH. Shells and SSH use what your system already has. For SSH sessions in tmux, tmux has to be installed on the remote machine.

## What's in this repository

This repository holds release notes and the issue tracker. Holler Bell's source code is not published here.

- **Releases:** what changed in each version. Installers are on [hollerbell.com](https://hollerbell.com/?ref=github#download), together with their SHA-256 checksums.
- **Issues:** bug reports and questions. See below.

## Report a bug

[Open an issue](https://github.com/hollerbell/holler-bell/issues/new/choose). Issues are public, so leave out anything you wouldn't post on the open web: tokens, passwords, private code, hostnames. Read through terminal output and check screenshots before you post them.

If you'd rather not report in public, write to [support@hollerbell.com](mailto:support@hollerbell.com).

Replies may come from Bellhop, an automated account of the Holler Bell team that uses an AI assistant; a person on the team is responsible for every reply.

## What phones home

Holler Bell runs on your machine. There's no account and no cloud relay, and your terminals never leave your computer. On its own, it contacts us for a single thing: the update check. Details are on the [privacy page](https://hollerbell.com/privacy/).

Your agents talk to their own providers under their own terms, not through us.

## License

Holler Bell is distributed under the [Holler Bell Free License](https://hollerbell.com/license/). It is not open source.

---

© 2026 FEO digital agency s.r.o. Not affiliated with Anthropic or OpenAI.
