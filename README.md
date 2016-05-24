Note: The game is still work in progress and not playable/installable yet.

# backgammonjs
`backgammonjs` is an extensible multiplayer backgammon game written in JavaScript.

Backgammon is one of the most popular and ancient board games and there are zillion implementations of it for PC and mobile crafted around the world.

## Main goals:
- Allow anyone to challenge friends or play with strangers online;
- Fair gameplay that is as close to real game as possible -  no visual hints for possible moves except those needed for basic interaction with the UI;
- Zero time to start the game - requires no registration or configuration;
- Works in browser @ PC & Mobile;
- Lightweight - playable on any device, even old ones - anything that can run a modern browser;
- Extensible and modular engine that would allow the open source community to implement different variants of the game as known in different countries.

## Future goals:
- Use good random generator with equal distribution;
- Allow players to send invites by chat or E-mail;
- Allow optional registration;
- Support player ratings;
- Remember game history;
- Create replay engine;
- Add multiple language support.

Check out [documentation](docs/design.md) for more details on design and architecture.

## Brief overview of project structure

The project is comprised of three components, each implemented by a separate package:
- Client application: [`backgammon.js-client`](client/README.md)
- Server application: [`backgammon.js-server`](server/README.md)
- Common Library: [`backgammon.js-lib`](lib/README.md)

More comming soon...

## How to install
Comming soon...

## Demo
Comming soon...

## More documentation for developers
Instructions on adding new variants of backgammon to the game can be found at [Creating rules for `backgammon.js`][docs/rules.md].
