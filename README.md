# Starbound-bardez-frackin-liquids-radioactive

This repo is a mod for [Starbound](https://playstarbound.com/), based on top of the following mods:
- [Frackin' Universe](https://steamcommunity.com/sharedfiles/filedetails/?id=729480149)
- [Molten Liquids tabs for Furnace: Fission Furnace Patch](https://steamcommunity.com/sharedfiles/filedetails/?id=2898371629) for organization
- [Frackin' Universe Research: Move Isotopes in Geology off to the left](https://steamcommunity.com/sharedfiles/filedetails/?id=2897239142) for research grid organization (also I won't support two versions of this branch of the grid)
- [mORE Liquids](https://steamcommunity.com/sharedfiles/filedetails/?id=1318339314) (for inspiration)

This repo was branched off of [Starbound-bardez-ore-liquids-frackin](https://github.com/BardezAnAvatar/Starbound-bardez-ore-liquids-frackin) and its original commit history reflects that of its originating repo

This mod does the following:
- [X] Adds in more liquids based on Frackin' Universe radioactive ores/isotopes/rods:
  - [X] Radioactive Ores
  | Liquid            | Liquid ID |
  |-------------------|-----------|
  | Liquid Plutonium  | 187       |
  | Liquid Uranium    | 188       |
  | Liquid Neptunium  | 189       |
  | Liquid Thorium    | 190       |
  - Things Not Done
    - Deuterium (already an FU liquid)
- [X] Adds isotope list (i.e. Gas Centrifuge only) centrifuge recipes to Frackin' Universe centrifuges for these liquids
  - [X] Liquid Plutonium
    - Yields Plutonium ore, oxygen, uranium ore
  - [X] Liquid Uranium
    - Yields Uranium ore, oxygen, thorium ore
  - [X] Liquid Neptunium
    - Yields Neptunium ore, oxygen, Plutonium ore
  - [X] Liquid Thorium
    - Yields Thorium ore, oxygen, lead (representing end of chain), unstable particles (representing Radium/Radon, alpha and beta decay, etc.)
- [X] Adds conversion recipes to the Fission Furnace for these liquids
  - [X] Liquid Plutonium
  - [X] Liquid Uranium
  - [X] Liquid Neptunium
  - [X] Liquid Thorium
- [X] Adds research recipes to the research system for these liquids
  - [X] Liquid Plutonium
  - [X] Liquid Uranium
  - [X] Liquid Neptunium
  - [X] Liquid Thorium
- TODO: Things I am not yet certain whether to do
  - Liquids I am debating
    - [ ] ~~Liquid~~ Gas Tritium
    - [ ] Liquid Ultronium