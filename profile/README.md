# Beacon

[beacons.gg](https://beacons.gg) is Beacon's home page. The site explains how Beacon works, and has
the [docs](https://beacons.gg/docs) and [Beacon Hosting](https://beacons.gg/hosting).

Beacon is a network of servers for games played at real places. Players place **rooms** on the map
and put signed **items** in them. Other players find those rooms and take the items out. A Beacon
server keeps the rooms consistent for every player who can see the same place.

Anyone can run a server. A game shows its players every server they trust, so a game built on Beacon
has no home server. The game's map is put together from servers that many people run.

## Repositories

| Repository                                                   | What the repository holds                                            | License    |
| ------------------------------------------------------------ | -------------------------------------------------------------------- | ---------- |
| [beacon.core](https://github.com/beacons-gg/beacon.core)     | the wire contract, the client SDK and the presets Beacon builds with | Apache-2.0 |
| [beacon.server](https://github.com/beacons-gg/beacon.server) | the server, its Atlas toolchain and the five-flow driver             | AGPL-3.0   |
| [beacon.admin](https://github.com/beacons-gg/beacon.admin)   | the operator console and its plugin contract                         | Apache-2.0 |

The packages are on npm under the [`@beaconsgg`](https://www.npmjs.com/org/beaconsgg) scope. The
server and console images are on GitHub Container Registry under `ghcr.io/beacons-gg`.

## Start here

- Learn how Beacon works: [beacons.gg](https://beacons.gg)
- Build a game: [beacons.gg/docs/building-a-game](https://beacons.gg/docs/building-a-game)
- Run a server: [beacons.gg/docs/run-a-server](https://beacons.gg/docs/run-a-server)
- Manage a server: [console.beacons.gg](https://console.beacons.gg)
- Report a bug or ask for a feature: [CONTRIBUTING.md](https://github.com/beacons-gg/.github/blob/main/CONTRIBUTING.md)
- Report a vulnerability: [SECURITY.md](https://github.com/beacons-gg/.github/blob/main/SECURITY.md)
- Anything else: `opensource@beacons.gg`
