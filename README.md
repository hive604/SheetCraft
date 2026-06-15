# SheetCraft

SheetCraft is a native iOS character sheet manager for 5e-compatible tabletop roleplaying games.

Create, organize, and play characters with a clean, touch-friendly interface designed specifically for mobile devices. SheetCraft stores characters as portable files, supports rich character details and portraits, and focuses on fast access at the table.

## Features

### Character Management

- Create and manage unlimited characters (SheetCraft Pro)
- Browse characters from a searchable library
- Assign custom character colors for quick identification
- Duplicate existing characters
- Soft-delete and restore characters from Trash

### Character Sheets

- Status tracking: hit points, temporary hit points, hit dice, death saves, inspiration, exhaustion, conditions and resource use (such as racial or class abilities). These values are editable even when the sheet isn't opened for editing.
- Ability scores and modifiers: saving throws, skills, passive scores, initiative tracking and proficiency options.
- Attack management: weapon names, effects (as notes), to hit bonuses, damage types and initiative bonuses.
- Spell management: spell slot tracking, prepared spells, ritual spells, concentration tracking, reaction spells, always-prepared spells.
- Character features and abilities. Resource tracking including rests is provided on status.
- Equipment tracking: quantities and notes.
- Biography: Character portraits, reference images, text background, personality notes and physical description.

### Import & Export

SheetCraft uses a portable `.sheetcraft` file format.

Each character can be:

- Exported for backup
- Shared with other players
- Imported on another device
- Archived outside the app

JSON character files can also be imported, which avoids the complexity of the binary format (which is zipped JSON + PNG).

## Storage

SheetCraft uses a hybrid storage model:

- Character data is stored as files on disk.
- SwiftData maintains a lightweight index for fast browsing and search.

This approach keeps character files portable while maintaining excellent performance for large collections. The file system directory (only) and index are compared on startup.

## Pro Features

SheetCraft Pro is a one-time purchase that unlocks:

- Unlimited characters
- Biography photo galleries

No subscriptions.

## Privacy

SheetCraft stores character data locally on device.

Character files are only shared when explicitly export or share them.

## Requirements

- iOS 26.2 or later

## Development

SheetCraft is written in Swift and SwiftUI.

Major technologies include:

- SwiftUI
- SwiftData
- StoreKit
- ZIPFoundation

## Status

SheetCraft is actively developed.

Current development focuses on:

- Character management improvements
- Workflow refinements
- Additional gameplay tools
- Continued UI polish

## Contributing

Bug reports and feature requests are welcome through the [public issue tracker](https://github.com/hive604/SheetCraft/issues).

When reporting a bug, please include:

- Device model
- iOS version
- Steps to reproduce
- Expected behavior
- Actual behavior

## License

Copyright © Hive 604.

All rights reserved.
