# romHack

This repository is set up as a small `Pokemon FireRed` ROM hack project using the `pret/pokefirered` decompilation as its base.

Current upstream base:

- `pret/pokefirered` commit `e060ab955`

## What This Repo Builds

The base project can build the following ROM images:

- `pokefirered.gba`
- `pokeleafgreen.gba`
- `pokefirered_rev1.gba`
- `pokeleafgreen_rev1.gba`
- `pokefirered_switch.gba`
- `pokeleafgreen_switch.gba`

For a small hack, we will usually focus on `pokefirered.gba`.

## First-Time Setup

1. Follow the dependency instructions in [INSTALL.md](INSTALL.md).
2. Place your legally obtained FireRed base ROM in the project root using the filename expected by the upstream instructions.
3. Run `make` to confirm the project builds cleanly before changing gameplay content.

## Good First Changes

- swap the starter Pokemon
- change early-route wild encounters
- add one custom NPC gift Pokemon
- tweak rival or intro text

## Notes

- This repo keeps its own git history and is not a clone of the upstream `pret` repository.
- The imported project files came from `pret/pokefirered`, but your hack-specific changes should live here.
