# HomePageX - Personal Start Page

HomePageX is a lightweight, self-contained personal start page that lets you organize your favorite links into customizable topic cards. Everything is stored locally in your browser (using IndexedDB + LocalStorage) - no server, no tracking, no installation needed.

## Features

- � **Fully local** - All data stays in your browser
- 🎨 **Customizable** - Change colors, wallpapers and layout
- 📂 **Topic cards** - Organize links into categories
- 🔍 **Quick search** - Press `/` to filter links
- 💾 **Backup/Restore** - Export/import your data as JSON
- 📱 **Responsive** - Works on desktop and mobile
- ⚡ **Single HTML file** - No build step, no dependencies

## Usage

1. Simply open the HTML file in your browser
2. Set it as your browser's home page for quick access
3. Use the toolbar to:
   - Add topics (categories)
   - Add links to each topic
   - Customize colors and appearance
   - Backup/restore your data

## Controls

- **Add Topic**: Creates a new category card
- **Add Link**: Adds a new link to a topic
- **Theme**: Customize colors and background
- **Backup**: Export/import your data
- **Reset**: Clear all data (with backup)

## Technical Details

- **Storage**: Uses IndexedDB for topics/links and LocalStorage for settings
- **Backups**: Exports all data as a JSON file
- **No Tracking**: Zero analytics, zero external requests
- **Accessibility**: Built with semantic HTML and ARIA

## Customization

You can modify the CSS variables at the top of the file to change:
- Colors (`--accent`, `--bg`, etc.)
- Spacing and sizes
- Fonts
- Border radius
- Shadows

## Browser Support

Works in all modern browsers that support:
- IndexedDB
- CSS Variables
- Flexbox/Grid

## License

Public Domain (Unlicense) - Use freely for any purpose

---

Tip: For quick setup, the app includes sample topics that are automatically created on first run. You can delete these and add your own.
