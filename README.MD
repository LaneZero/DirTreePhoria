# DirTreePhoria 

## Core Features

-   Generate visual tree structure of directories and files
-   Multiple export formats supported:
    -   TXT (plain text)
    -   JSON (data structure)
    -   HTML (interactive browser view)
-   Advanced text-based UI with interactive menus
-   Smart filtering system
-   Full English and Persian language support

## Advanced Capabilities

### HTML Output

-   Interactive tree view with expandable/collapsible nodes
-   Custom CSS styling
-   Search functionality within tree structure
-   Detailed information on hover
-   Light/Dark theme support
-   Printable tree structure

### Advanced Filtering

-   Filter by:
    -   File extensions
    -   File/folder names
    -   File sizes
    -   Creation/modification dates
    -   Regex patterns
-   Custom exclusion rules
-   Adjustable tree depth

### Settings & Customization

-   Full configuration via JSON
-   Customizable display format
-   Color and symbol customization
-   Save/load custom settings
-   Multiple profile support

### Technical Features

-   Optimized processing for large directories
-   Error handling and input validation
-   Progress tracking
-   Relative/absolute path support
-   PowerShell Core compatible

## System Requirements

-   PowerShell 5.1 or higher
-   Minimum system requirements:
    -   RAM: 2GB
    -   Storage: 50MB free space
-   Administrative privileges (optional)

## Installation

```powershell
# Clone repository
git clone https://github.com/LaneZero/DirTreePhoria.git

# Navigate to directory
cd DirTreePhoria

# Run the script
.\TreeGenerator.ps1

```
## Usage Examples

#### Basic usage
.\TreeGenerator.ps1

#### Generate HTML tree
.\TreeGenerator.ps1 -Path "C:\Projects" -Format "HTML"

#### Custom filtering
.\TreeGenerator.ps1 -ExcludePattern "node_modules|.git" -MaxDepth 3

---
## Configuration

```json

`{
  "defaultFormat": "HTML",
  "theme": "dark",
  "excludePatterns": [
    "node_modules",
    ".git",
    "bin",
    "obj"
  ],
  "maxDepth": 5
}` 

```

## Contributing

Contributions are welcome! Please read our contributing guidelines and submit pull requests to our repository.

## License

This project is licensed under the MIT License - see the LICENSE file for details.