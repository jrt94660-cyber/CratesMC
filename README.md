# CratesMC (license-free recreation)

A fresh Paper plugin recreation based on the configuration files bundled with SMPCrate 26.3. This project does not use license activation.

## Target
- Paper 1.21.x (Java 21)
- Built with Gradle
- Plugin entry: `/sc` (aliases: `/crate`, `/crates`, `/smpcrate`, `/smpcrates`)

## Commands
- `/sc` - help
- `/sc view <crate>` - preview configured reward selection menu
- `/sc bind <crate>` - right-click a block to bind it to a crate
- `/sc givekey <player> <crate> <amount>`
- `/sc keyall <crate> <amount>`
- `/sc realkeygive <player> <crate> <amount>`
- `/sc realkeyall <crate> <amount>`
- `/sc keylist <player>`
- `/sc keytake <player> <crate> <amount>`
- `/sc keyclear <player>`
- `/sc reload`

Permission: `cratesmc.admin` for crate administration; `cratesmc.use` is the command permission in plugin.yml.

## Config
Default crate definitions, key materials/names/lore, reward item details, enchantments and reward commands are in `config.yml`. Edit the `crates` and `keys` sections to customize crates and rewards.

## Build
The GitHub Actions workflow builds the plugin with Gradle and uploads a `CratesMC-jar` artifact on each push to main or manual workflow dispatch.
