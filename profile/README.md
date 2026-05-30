# Imperial Bower

<img
    align="left"
    width="125"
    height="174"
    src="https://github.com/ImperialBower/.github/blob/main/profile/images/imperial_bower.jpg" />

Rust-first poker library ecosystem, from card primitives to GTO solvers and gRPC services.

**Imperial Bower** was an early term for a Joker. Jokers were first introduced in the card game Euchre, called the "Best Bower." Samuel Hart is credited with printing the first illustrated "Best Bower" card in 1863 with his "Imperial Bower".

— [Wikipedia](https://en.wikipedia.org/wiki/Joker_(playing_card))

<br clear="left"/>

## Ecosystem

### Core Libraries

| Repository | Description |
|------------|-------------|
| [pkcore](https://github.com/ImperialBower/pkcore) | Core poker evaluation engine: hand ranking, CFR solvers (Kuhn, DCFR), and odds calculation |
| [ckc-rs](https://github.com/ImperialBower/ckc-rs) | Isolated Cactus Kev hand evaluator — the high-performance inner loop inside pkcore |
| [cardpack.rs](https://github.com/ImperialBower/cardpack.rs) | Generic multi-deck card library supporting French, Euchre, Pinochle, Tarot, and more |
| [wincounter](https://github.com/ImperialBower/wincounter) | Win/loss/tie counter utilities for hand equity calculations |

### Language Bindings & Runtimes

| Repository | Description |
|------------|-------------|
| [pkpy](https://github.com/ImperialBower/pkpy) | Python bindings for pkcore |
| [pknotebook](https://github.com/ImperialBower/pknotebook) | Jupyter (All Spark) notebook image bundling pkcore and pkpy |
| [pktui](https://github.com/ImperialBower/pktui) | Rust Ratatui Console Client for pkcore |

### Services & APIs

| Repository | Description |
|------------|-------------|
| [pkdealer](https://github.com/ImperialBower/pkdealer) | gRPC server exposing pkcore over the network |
| [pkapi](https://github.com/ImperialBower/pkapi) | Protocol Buffer definitions for the PK engine |
| [pkstate](https://github.com/ImperialBower/pkstate) | Serialization format for poker game state |

### WASM Examples 

| Repository | Description |
|------------|-------------|
| [pkgto-web](https://github.com/ImperialBower/pkgto-web) | WebAssembly-powered GTO preflop equity analyzer |
| [pkkuhn-web](https://github.com/ImperialBower/pkkuhn-web) | WebAssembly-powered interactive Kuhn poker game |
| [pkarena0-web](https://github.com/ImperialBower/pkarena0-web) | WebAssembly-powered player arena |

### Predecessors

| Repository | Description |
|------------|-------------|
| [fudd](https://github.com/ImperialBower/fudd) | Original Rust poker library (superseded by pkcore) |


