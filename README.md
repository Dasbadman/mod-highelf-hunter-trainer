# High Elf Hunter Trainers

This ropey litle addon for abracadaniel22's excellent [AzerothCore High Elf custom race](https://github.com/abracadaniel22/azerothcore-highelf) adds hunter trainers to Elwynn Forest including a Taming the Beast quest chain.

## Overview
- Adds a hunter trainer to Northshire Abbey with a corresponding meet-the-trainer quest available from Marshal McBride.
- Adds a hunter trainer and pet trainer to Goldshire with a corresponding Taming the Beast quest chain.

## Installation

1. Apply `highelfhunter.patch` to `azerothcore-wotlk` directory
2. Copy `(vanilla|ind-prog)/build/DBFilesClient/*.dbc` to client dbc directory depending on whether you are using individual progression or not.
3. Apply `data/sql/world/base/highelf_hunter_quests.sql` to acore_world (should automatically do so with a docker build (hopefully)).
4. Copy `(vanilla|ind-prog)/Patch-W.mpq` to your client's data directory depending on whether you are using individual progression or not.

Bug reports and contributions are welcome and appreciated :pray:
