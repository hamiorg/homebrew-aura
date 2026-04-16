# homebrew-aura

Homebrew tap for [aura](https://github.com/hamiorg/aura) — the AURA toolchain CLI.

## Install

```bash
brew install hamiorg/aura/aura
```

This is shorthand for:

```bash
brew tap hamiorg/aura
brew install aura
```

## Upgrade

```bash
brew upgrade aura
```

## Uninstall

```bash
brew uninstall aura
brew untap hamiorg/aura
```

## About

`aura` compiles `.aura` source files into binary artifacts for the Hami / Triverse platform:

| Output   | Description                                        |
| -------- | -------------------------------------------------- |
| `.atom`  | Flat-array augmented interval tree for sync meshes |
| `.hami`  | B-Tree manifest (credits, vocab, availability)     |
| `.atlas` | DTW warp path for variant stream alignment         |

It also manages project history (takes, marks, streams) and scaffolds new AURA projects.

See the [main repository](https://github.com/hamiorg/aura) for full documentation.
