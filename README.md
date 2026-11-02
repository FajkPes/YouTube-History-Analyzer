# YouTube History Analyzer

A private, offline dashboard for exploring your personal YouTube watch history exported through Google Takeout.

I created this project because the raw `watch-history.json` file is difficult to understand on its own. The analyzer turns it into a clear overview of viewing habits while keeping the data on your computer.

## Highlights

- Total and unique videos and channels
- Regular videos, Shorts, and music breakdown
- Activity by hour, weekday, and month
- Most watched channels and repeated videos
- Active-day coverage and watch streaks
- Configurable estimated watch time
- Custom Shorts and music classification rules
- Import and export of classification settings
- English interface by default, with an optional Czech language switch
- Fully local processing: the selected history file is not uploaded anywhere

## Requirements

- Windows, macOS, or Linux
- A modern web browser
- Your extracted YouTube `watch-history.json` file

No installation, Node.js, server, internet connection, or third-party dependency is required.

## Get your YouTube history

1. Open [Google Takeout](https://takeout.google.com/).
2. Deselect everything, then select **YouTube and YouTube Music**.
3. Include your history data and create the export. Choose JSON when the export options offer a format choice.
4. Download and extract the Takeout archive.
5. Locate `watch-history.json`, usually under `YouTube and YouTube Music/history/`.

Google may change the exact Takeout labels or folder layout. See the [official Google Takeout help](https://support.google.com/accounts/answer/3024190?hl=en) if the current interface differs.

## How to use

1. Download and extract the release ZIP.
2. Run `Start YouTube History Analyzer.bat`, or open `index.html` directly.
3. Drop `watch-history.json` onto the import area, or click the area and choose the file.
4. Review the dashboard and adjust its date range, filters, or sorting.
5. Open **Detection Settings** to tune Shorts, music, artists, and keyword classification.

The app accepts the extracted JSON file, not the complete Takeout ZIP or TGZ archive.

## Privacy

All parsing and statistics run inside your browser. The application contains no analytics, uploads, external scripts, or network requests. Keep your personal Takeout archive private and do not publish it with the project.

[Detailed documentation](README-DETAILS.md) · [All releases](https://github.com/FajkPes/YouTube-History-Analyzer/releases)

## Credits

**Idea, concept and design:** FajkPes  
**Coding:** ChatGPT Codex, Claude and Google Antigravity
