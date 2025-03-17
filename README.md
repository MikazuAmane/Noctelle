![Icon](https://github.com/MikazuAmane/Noctelle/blob/main/Assets/NoctelleIcon.ico?raw=true)
# Noctelle
A tool for crafting branching game dialogues with preset validation for characters, expressions, positions, and actions. JSON/XML Import/Export support.

## Usage
- Update Data/.json files to meet your projects environment and needs
- Share Data/.json with writers in the same environment
- Export dialogue to .json or .xml
- Import into game engine/program of choice
- Parse formatted data

## Customize Data Sets
Noctelle features three seperate .json files in the Data directory,
These will act as references and guides for the writers in what can be used for the specific game environment, for validation and spelling error checks.

### Characters.json
Define characters and expressions
- Id: Internal character id
- Name: Display name for character
- Expressions: List of expressions for targeting specific character images

### Positions.json
Define screen positions for character image placement
- Id: String id of screen position

### Actions.json
Define custom logic
- Id: Action reference id
- PossibleValues: Definition for additional parameters and default/possible values/types for those parameters
