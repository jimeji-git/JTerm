# JTerm

**One terminal workspace across iPhone, iPad, and Mac.**

[English](README.md) · [中文](README.zh-CN.md)

[![Download on the App Store](https://tools.applemediaservices.com/api/badges/download-on-the-app-store/black/en-us?size=250x83)](https://apps.apple.com/app/id6780185815)

JTerm is a native SSH terminal and remote-work toolkit for Apple devices. It keeps your hosts, keys, reusable commands, hosts mappings, and personal-device network information in one workflow, so moving from Mac to iPad or iPhone requires less setup and repetition.

No JTerm account is required. Your personal workspace syncs through your iCloud account.

## One configuration, three devices

- **iPhone — quick fixes anywhere.** Check a service, read logs, confirm a job, or run a saved command. A terminal key row keeps Esc, Ctrl, Alt, Tab, arrow keys, and common symbols within reach.
- **iPad — a larger mobile workspace.** Use the sidebar, flexible layouts, and a hardware keyboard for longer sessions, host switching, and remote file work.
- **Mac — organize and operate.** Manage multiple SSH sessions, hosts, groups, keys, saved commands, clipboard favorites, and hosts mappings in a keyboard-first workspace.

## What syncs through iCloud

- SSH host details, groups, ordering, and jump-host relationships
- Key records and host-to-key assignments
- Saved commands and text favorites, including aliases and categories
- Hosts-mapping profiles, reusable variables, and selected values
- “My Machines” device names, platforms, and active network-interface addresses

Passwords, private keys, and key passphrases are protected by Apple Keychain. Cross-device credential availability depends on iCloud Keychain. Appearance settings are stored separately for iPhone, iPad, and Mac device classes.

JTerm syncs configuration and reusable information—not active SSH connections or live terminal screens.

## Enhanced clipboard

On Mac, JTerm can search text and image history, pin entries, organize text favorites with aliases and categories, prioritize frequently used items, and send a saved command to the active terminal.

Regular clipboard history and image favorites remain local to the Mac. Text favorites and categories can sync through your personal iCloud account for reuse on iPhone and iPad. Install the optional **JTerm Shortcut** companion to open the floating clipboard panel from other Mac apps with **⌘⇧V**.

## Hosts mapping by environment

Create named hosts profiles for development, testing, or other environments. Enable or disable groups, reuse variables such as **DEV_IP**, keep multiple candidate values, preview the final result, and check duplicate hostnames before applying.

Profiles and variables sync across devices. You can edit them on iPhone or iPad; applying them to **/etc/hosts** happens on a Mac through JTerm Shortcut and requires administrator authorization the first time. JTerm preserves content outside its managed blocks.

## My Machines

“My Machines” helps answer: *What IP address does my other device have now?*

- See the device name, platform, and current-device marker
- Inspect IPv4 and IPv6 addresses by network interface
- Copy an address for a connection or debugging session
- Review its update time and iCloud sync status
- Refresh manually or report changes while JTerm is running

This is not a network scanner and does not enable SSH or public access. A connection still requires a reachable network and a running destination service. Sleeping devices or closed apps may show the most recently reported information rather than live presence.

## Terminal and remote-management features

- xterm-compatible terminal rendering
- Password and SSH private-key authentication
- Multiple concurrent sessions and automatic reconnection
- SFTP browsing and file transfer
- Multi-level jump hosts
- Search, selection, scrollback, themes, and configurable fonts
- Optional AI assistance using your own provider, endpoint, model, and API key

## A practical cross-device workflow

1. Organize hosts, keys, groups, and command favorites on Mac.
2. Continue on iPad with the same synced connection details and reusable text.
3. Handle quick checks from iPhone and look up device addresses in My Machines.
4. When an environment changes, update a hosts profile, sync it, preview it on the target Mac, and apply it there.

## Download and links

- [Download JTerm on the App Store](https://apps.apple.com/app/id6780185815)
- [JTerm website and JTerm Shortcut](https://jterm.jimeji.com/)
- [Detailed JTerm workflow article](https://blog.csdn.net/j0341326/article/details/163315331)
- [中文版 README](README.zh-CN.md)

---

JTerm is developed by [Jimeji](https://jimeji.com/).
