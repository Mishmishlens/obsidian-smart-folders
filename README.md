# Smart Folders for Obsidian

Create smart folders based on tag queries, similar to Apple Notes Smart Folders functionality. Automatically organize and view your notes based on their tags with real-time updates.

## Features

- 🗂️ **Smart Folders**: Create virtual folders that automatically collect notes based on tag queries
- 🔄 **Real-time Updates**: Automatically refreshes when notes are modified, created, or deleted
- 🔍 **Advanced Queries**: Support for AND, OR, and NOT operators in tag queries
- 📱 **Clean UI**: Dedicated sidebar view with easy file access
- ⚙️ **Customizable**: Configurable refresh intervals and easy folder management

## Usage

1. Click the folder-search icon in the ribbon or use Command Palette → "Smart Folders"
2. Click the "+" button to create a new smart folder
3. Enter a name and tag query (e.g., `#work`, `#project AND #todo`)
4. Your smart folder will automatically show matching notes and update in real-time

### Query Examples

- Basic tag: `#work`
- Multiple tags: `#project AND #todo`
- Alternative tags: `#work OR #personal`
- Exclusions: `NOT #completed`
- Complex: `#project AND (#todo OR #in-progress) AND NOT #completed`

## Installation

### From Obsidian Community Plugins (Coming Soon)
1. Open Settings → Community Plugins
2. Search for "Smart Folders"
3. Install and enable

### Manual Installation
1. Download the latest release from GitHub
2. Extract to `.obsidian/plugins/smart-folders/`
3. Enable in Settings → Community Plugins

## Development

```bash
npm install
npm run dev
