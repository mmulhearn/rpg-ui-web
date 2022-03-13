# RPG
The goal of RPG is to create a browser-based RPG.  The initial development will be to support D&D but it should be architected to allow future expansion into other RPGs.

## Technology
- Web: SPA, either Angular or React
- Communication: HTTP polling or web sockets (if web sockets can be done very cheaply)
- Server: .NET Core
- Data Stores: Cosmos?

## Features
- Character sheet management
  - Create character wizard
  - Level up help
  - Inventory tracking
  - Equipment tracking
  - Money tracking
  - Health and conditions tracking
  - Actions (spells, weapons, physical movement)
- Custom maps
  - Grid systems (square vs hex)
  - Terrain types (regular, rough, non-inabitable like trees, etc)
  - Movement system (allow user to select path to move through)
  - Show active AoE
- Items
  - Preconfigured weapons
  - Preconfigured armor
  - Preconfigured items
  - Allow custom weapons, armor and items
- Spells
  - Preconfigured spells
  - Allow custom spells and effects
- Combat
  - Target enemies and allies with attacks and spells
    - Auto-add and -deduct HP
    - Auto-add and -remove conditions based on spells
  - Show ranges of actions
  - Combat order/turn tracker
  - Health meters (for allies)

## Architecture

## Work Management
Azure DevOps will be used to track work items for feature development.

## Contributing
Cut branch, develop, PR back into `main`.

## CI/CD
While currently disabled, AzureDevops CI/CD pipelines will probably be used.
