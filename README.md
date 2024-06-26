# AI2SQL Generator

AI2SQL Generator is an innovative desktop application that uses artificial intelligence to convert natural language queries into SQL statements, making database interactions more intuitive and efficient for users of all skill levels.

## Features

- AI-powered SQL generation from natural language input
- Database connection management
- Query execution and result display
- User-friendly interface for both Windows and macOS

## Installation

### Windows
AI2SQL Generator is distributed as a portable .exe file for Windows x64 systems. No installation is required.

1. Download the latest Windows release (`AI2SQL-Generator-Portable.exe`) from the [Releases](https://github.com/mergisi/AI2SQL-Generator/releases/download/v1.0.2/AI2SQL.Generator-Portable-1.0.0.exe) page.
2. Run the `AI2SQL-Generator-Portable.exe` file directly.

### macOS
For macOS users, AI2SQL Generator is available as a .dmg installer.

1. Download the latest macOS release (.dmg file) from the [Releases](https://github.com/mergisi/AI2SQL-Generator/releases/tag/v1.0.3) page.
2. Open the downloaded .dmg file.
3. Drag the AI2SQL Generator app to your Applications folder.
4. Eject the disk image.
5. Launch AI2SQL Generator from your Applications folder or Spotlight.

Note for macOS users: If you encounter a security warning when first opening the app, right-click (or Control-click) on the app icon and select "Open" from the context menu.

### Security Warnings and How to Proceed

Sometimes, Windows or macOS may prevent the app from running due to security measures. Here's what to do:

#### Windows Users

If Windows SmartScreen prevents the app from running:

1. When the warning appears, click on "More info".
2. Then click on "Run anyway".

If you receive a "Windows protected your PC" message:

1. Click on "More information".
2. Then click "Run anyway".

#### macOS Users

If macOS prevents the app from opening because it's from an unidentified developer:

1. Right-click (or Control-click) on the AI2SQL Generator app in your Applications folder.
2. Select "Open" from the context menu.
3. Click "Open" in the dialog box that appears.

Note: You only need to do this the first time you run the application. After that, you can open it normally.

If you see a message that the app is damaged:

1. Open System Preferences.
2. Go to Security & Privacy.
3. Click the General tab.
4. Click the lock and enter your password to make changes.
5. Under "Allow apps downloaded from," select "App Store and identified developers" if it isn't already selected.

If you still can't open the app:

1. Open Terminal.
2. Type: `xattr -dr com.apple.quarantine ` (include the space at the end).
3. Drag the AI2SQL Generator app into the Terminal window and press Enter.

These steps should allow you to run the application. If you continue to experience issues, please contact our support team.


## System Requirements

### Windows
- Windows 10 or later (64-bit)
- 4GB RAM (minimum)
- 100MB free disk space

### macOS
- macOS 10.13 (High Sierra) or later
- 4GB RAM (minimum)
- 100MB free disk space

## Usage

1. Launch AI2SQL Generator.
2. Set up your database connection in the "Data Sources" section.
3. Navigate to the "SQL Generator" section.
4. Select your database and relevant tables.
5. Enter your query in natural language.
6. Click "Generate SQL" to create the SQL statement.
7. Review and execute the generated SQL if desired.

## License Management

AI2SQL Generator operates on a usage-based licensing model:

- Each installation comes with an initial set of query generations.
- When you reach your limit, you'll need to upgrade your license to continue using the application.
- To upgrade, follow the prompts in the application or contact our support team.

## Support

For issues, questions, or to obtain an upgrade key, please contact our support team at support@ai2sql.io or [open an issue](https://github.com/mergisi/AI2sql-Generator/issues) on this repository.

## Privacy and Security

AI2SQL Generator processes queries locally and does not store your database information or queries. However, please ensure you have necessary permissions before generating SQL for any sensitive data.

## Feedback

We value your input! Please open an issue in this repository for bug reports or feature requests. Your feedback helps us improve AI2SQL Generator.

## Disclaimer

This software is provided "as is", without warranty of any kind. Use at your own risk. Always review generated SQL before execution in production environments.

## Acknowledgements

- OpenAI for the GPT model used in SQL generation

---

Thank you for using AI2SQL Generator! We're constantly working to improve our application and appreciate your support.
