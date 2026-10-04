<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/hb-mark-dark.svg">
    <img src="assets/hb-mark-light.svg" width="72" height="72" alt="">
  </picture>
</p>

<h1 align="center">Holler Bell</h1>

<p align="center">
  <strong>All your agents. One window.</strong><br>
  A desktop app for Claude Code, Codex, shells and SSH.<br>
  When an agent finishes and waits for you, Holler Bell shows you which session it is.
</p>

<p align="center">
  <a href="https://hollerbell.com/?ref=github#download"><strong>Download for Windows, macOS and Linux</strong></a><br>
  Free, at home and at work. No account and no license key.
</p>

<p align="center">
  <img src="assets/window-6-dark.png" width="830" alt="The Holler Bell window: the list of sessions on the left, six of them open side by side, and the count of waiting sessions in the header">
</p>

<p align="center">This repository holds release notes and the issue tracker. Holler Bell's source code is not published here.</p>

## Three agents, a shell, an SSH box. Which is waiting for you?

### See who's waiting

A waiting session gets an amber mark and a notification, and the waiting count goes up. Working sessions stay quiet.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/waiting-dark.png">
  <img src="assets/waiting-light.png" width="830" alt="Waiting sessions: their rows carry an amber mark, the header counts the ones you have not looked at yet, and one of them is open with its question">
</picture>

### Every session, grouped by folder

Sessions sit under the folder they run in. Collapse the folders you're not working in. SSH sessions show the host they're connected to.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/folders-dark.png">
  <img src="assets/folders-light.png" width="480" alt="The list of sessions grouped by folder, with SSH sessions under their hosts">
</picture>

### Resume after a restart

After a restart, "Resume all" brings your sessions back. Agents continue their conversations and SSH sessions in tmux reconnect. Plain shells start fresh.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/resume-dark.png">
  <img src="assets/resume-light.png" width="520" alt="After a restart: the Restore tab with the Resume all button and the sessions to bring back">
</picture>

### Views for each task

Put the sessions for a task side by side and switch between views with a click.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/window-2-dark.png">
  <img src="assets/window-2-light.png" width="830" alt="A view with two sessions side by side; the tabs above them switch to other views">
</picture>

### Also in the window

- **Waiting queue.** Click the waiting count to jump to the session that has waited longest.
- **Terminal bell.** A program that rings BEL in its terminal marks the session as waiting.
- **SSH in tmux.** Choose tmux when you open an SSH session, and it survives a dropped connection.
- **Names that stick.** Name your shells and SSH sessions. The names survive a restart.

The screenshots show made-up sessions. Session types appear as the monograms CLD and CDX.

## Get started

1. **[Download the installer](https://hollerbell.com/?ref=github#download)** for your system. Holler Bell runs on Windows, macOS 12 Monterey or later, and Linux.
2. **Install Claude Code or the Codex CLI** and make sure it's on your PATH. Shells and SSH use what your system already has. For SSH sessions in tmux, tmux has to be installed on the remote machine.
3. **Start your first session.** On the "This machine" card, open the "New" tab, pick a folder and press ▶ on the Claude Code or Codex CLI row.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/new-dark.png">
  <img src="assets/new-light.png" width="520" alt="The New tab on the This machine card, with the rows Claude Code and Codex CLI">
</picture>

## What phones home

Holler Bell runs on your machine. There's no account and no cloud relay, and your terminals never leave your computer. On its own, it contacts us for a single thing: the update check. Details are on the [privacy page](https://hollerbell.com/privacy/).

Your agents talk to their own providers under their own terms, not through us.

## Report a bug

[Open an issue](https://github.com/hollerbell/holler-bell/issues/new/choose). Issues are public, so leave out anything you wouldn't post on the open web: tokens, passwords, private code, hostnames. Read through terminal output and check screenshots before you post them.

If you'd rather not report in public, write to [support@hollerbell.com](mailto:support@hollerbell.com).

Replies may come from Bellhop, an automated account of the Holler Bell team that uses an AI assistant; a person on the team is responsible for every reply.

## Releases

[Releases](https://github.com/hollerbell/holler-bell/releases) say what changed in each version. Installers are on [hollerbell.com](https://hollerbell.com/?ref=github#download), together with their SHA-256 checksums.

## Also from us

**[Cache Bell](https://github.com/hollerbell/cache-bell)** is a plugin for Claude Code. It saves your tokens and limits: it stops a long session from spending them on re-sending its whole context after a break. Experimental; its code is public under the MIT license.

## License

Holler Bell is distributed under the [Holler Bell Free License](https://hollerbell.com/license/). It is not open source.

---

© 2026 FEO digital agency s.r.o. Not affiliated with Anthropic or OpenAI.
