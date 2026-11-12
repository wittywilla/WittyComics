# Changelog

What changed in WittyComics, newest first. What changed before it had a repository of its own is in the
[WittyMediaServer changelog](https://github.com/wittywilla/WittyMediaServer/blob/master/CHANGELOG.md).

## Unreleased

- **Settings in every app's Settings, under Modules** (`sdui.json`, each profile's own): the layout, direction and fit a comic opens with the first time. Each comic still keeps what you choose while reading it, and manga and strips open as they say. The reading surface itself stays in the reader.
- A page image that can't be shown is now reported to the host's log (`host.report`), once per page.
- **Module API 4**, for WittyMediaServer 0.8.0-alpha and later: the module carries its own server-driven UI in `sdui.json`, which `wittymodule pack` puts in every archive.
- Carries `sdui.json` with its theme scope, so an administrator can give the comics reader colours of its own. Its pages come with WittyInk, which every reader shares.
- **WittyComics 0.3.0:** Fits WittyMediaServer 0.8.x.

- Module API 3 and WittyMediaServer 0.6.0-alpha: this is how a server gets it now, with no copy compiled in.
- WittyComics is now a project of its own, developed and released from this repository.
