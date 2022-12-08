# Starbound-bardez-frackin-liquids-radioactive

This repo is a mod for [Starbound](https://playstarbound.com/), based on top of the following mods:
- [Frackin' Universe](https://steamcommunity.com/sharedfiles/filedetails/?id=729480149) 
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
- [ ] Adds conversion recipes to the Fission Furnace for these liquids
- [ ] Adds research recipes to the research system for these liquids
  - [ ] Radioactive Ores
    - [ ] Liquid Plutonium
    - [ ] Liquid Uranium
    - [ ] Liquid Neptunium
    - [ ] Liquid Thorium
- [ ] Adds liquid mixing reactions
  - [ ] TODO: what reactions do I want to add?
    - All of the radioactive ones should net some fun interactions to other radioactive liquids
      - neptunium->plutonium->uranium -> thorium
- TODO: Things I am not yet certain whether to do
  - Liquids I am debating
    - [ ] ~~Liquid~~ Gas Tritium
    - [ ] Liquid Ultronium