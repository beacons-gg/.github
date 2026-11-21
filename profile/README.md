# [Beacon](https://beacons.gg/)

Beacon is a decentralized server network for location-based games. Beacon gives developers shared
infrastructure for building games around real-world places, without having to build and operate
their own multiplayer backend.

Using the [Beacon Client SDK](https://www.npmjs.com/package/@beaconsgg/client-sdk), games can create
rooms, manage items, coordinate player interactions, and work with persistent world state across
multiple servers. Each game defines its own mechanics and data, while Beacon handles player
identities, signed operations, and shared state consistency.

## One network, many games

- **Build with the SDK.** Integrate Beacon into your game using the
  [Client SDK](https://www.npmjs.com/package/@beaconsgg/client-sdk). Player identities, server
  discovery, shared state, and live updates are handled by Beacon, leaving you to focus on your
  game's mechanics and experience.
- **Share infrastructure.** Multiple games can use the same servers. Each game maintains its own
  rooms and items, with the ability to open up specific interactions to other games.
- **Decentralized by design.** There is no central game server or single network owner. Players
  choose which servers they trust, and games combine those servers into a single map. Anyone can
  operate a server for their community, region, or game.
- **Host it your way.** Run your own server using the open-source
  [Beacon Server](https://github.com/beacons-gg/beacon.server), use servers operated by other
  communities, or deploy your servers through [Beacon Hosting](https://beacons.gg/hosting).
- **Grow with the network.** New servers expand the map for every game they admit. New games can
  start using infrastructure that's already running.

## Get started

Explore the [Beacon homepage](https://beacons.gg/), read the
[developer documentation](https://beacons.gg/docs), integrate the
[Client SDK](https://www.npmjs.com/package/@beaconsgg/client-sdk), or get started with
[Beacon Hosting](https://beacons.gg/hosting). Server operators manage their servers in the
[operator console](https://console.beacons.gg).

## Repositories

| Repository                                                   | What the repository holds                                            | License    |
| ------------------------------------------------------------ | -------------------------------------------------------------------- | ---------- |
| [beacon.core](https://github.com/beacons-gg/beacon.core)     | the wire contract, the client SDK and the presets Beacon builds with | Apache-2.0 |
| [beacon.server](https://github.com/beacons-gg/beacon.server) | the server, its Atlas toolchain and the five-flow driver             | AGPL-3.0   |
| [beacon.admin](https://github.com/beacons-gg/beacon.admin)   | the operator console and its plugin contract                         | Apache-2.0 |

The packages are on npm under the [`@beaconsgg`](https://www.npmjs.com/org/beaconsgg) scope. The
server and console images are on GitHub Container Registry under `ghcr.io/beacons-gg`.

## Contact

- Report a bug or ask for a feature: [CONTRIBUTING.md](https://github.com/beacons-gg/.github/blob/main/CONTRIBUTING.md)
- Report a vulnerability: [SECURITY.md](https://github.com/beacons-gg/.github/blob/main/SECURITY.md)
- Anything else: `opensource@beacons.gg`
