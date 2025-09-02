# Code Spec

A powerful desktop application that generates comprehensive project specifications, requirements, and task lists using AI technology.

## Features

- **Intelligent Specification Generation**: Create detailed project specifications from codebase analysis
- **Requirements Documentation**: Generate comprehensive requirements documents
- **Task List Creation**: Automatically break down projects into actionable tasks
- **Codebase Analysis**: Deep analysis of existing codebases for context-aware generation
- **Multiple Output Formats**: Export specifications in various formats
- **User-Friendly Interface**: Intuitive PyQt6-based desktop application

## Installation

### Option 1: Download Executable (Recommended)

1. Download `AI-Specification-Generator.exe` from the releases section
2. Run the executable directly - no installation required!

### Option 2: Run from Source

1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run: `python main.py`

## System Requirements

- Windows 10/11 (64-bit)
- 4GB RAM minimum, 8GB recommended
- 500MB free disk space
- Internet connection for AI API calls

## Usage

1. Launch the application
2. Configure your AI API settings
3. Select or upload your codebase
4. Choose the type of specification to generate
5. Review and export the generated documents

## Recent Fixes

### Version 1.1 - Permission Issues Resolved

- **Fixed Permission Denied Errors**: Application now uses user-writable directories instead of trying to create files next to the executable
- **Improved Logging**: Logs are now stored in `~/.ai-spec-generator/logs/` or system temp directory
- **Better Error Handling**: Enhanced error handling for file system operations
- **Cross-User Compatibility**: Application works regardless of where the executable is placed

## Troubleshooting

### Common Issues

1. **"Permission Denied" Error**: This has been fixed in v1.1. If you still encounter this, ensure you're running the latest version.

2. **Slow Startup**: The application may take a moment to initialize AI components on first run.

3. **Missing Dependencies**: If running from source, ensure all requirements are installed.

## File Locations

- **Logs**: `%USERPROFILE%\.ai-spec-generator\logs\`
- **Output**: `%USERPROFILE%\.ai-spec-generator\output\`
- **Uploads**: `%USERPROFILE%\.ai-spec-generator\uploads\`
- **Assets**: `%USERPROFILE%\.ai-spec-generator\assets\`

## Support

If you encounter any issues, please check the log files in the locations mentioned above for detailed error information.

## License

This project is licensed under the MIT License - see the LICENSE file for details.