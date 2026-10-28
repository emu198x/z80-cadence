# z80-cadence

The cadence every Z80 machine shares: two CPU half-cycles per T-state, interrupt pins fed before each.

| Crate | Registry |
|---|---|
| [`emu198x-z80-cadence`](crates/emu198x-z80-cadence) | [crates.io](https://crates.io/crates/emu198x-z80-cadence) |

Part of [Emu198x](https://github.com/emu198x/emu198x), a family of
cycle-accurate retro-computing emulators. Used by thirteen Z80 machines across eleven families, from the CPC to the Tatung Einstein.

Each crate is versioned on its own and bumps only when it changes. Releases go
through release-plz: merging its release pull request tags the crate and
publishes it.

Licensed GPL-2.0-or-later.
