# Curator

Curates your perfect MAME collection based on your preferences. While it runs in the terminal, it is made to be easy to understand and use! Lots of explanation is provided at request along the way. It uses the MAME internal database, plus additional files to create filterable attributes for each game. Rebuilder is used to build your collection from source folders.

## Operating System Compatibility:
Windows 7/8/10/11

## Capabilities:

- Can create 1G1R style sets. Choose best rom variation based on number of players and language. Can prefer US releases.
- Many different filters to eliminate games you can't play or don't want to play:
  - Year
  - Genre and category
  - Language
  - Control types
  - Emulation compatibility
  - Games requiring CHDs
  - "Adult" games
  - NES and SNES games
  - Prototypes
  - Hacks and bootlegs
- Easily eliminate games you wouldn't find in an arcade (non-games, screenless games, devices, bioses, etc.)
- Includes only the samples you need. Also remove games that require samples you don't have.
- Keep latest prototype for unreleased games.
- Optionally recompress in 7z for smaller file sizes.

## Known Issues:

- Year filtering doesn't account for incomplete MAME database entries (i.e. 198?, 19??, etc.) These games will be discarded. It requires more investigation, but I believe this is typically found on hacks, bootlegs, and prototypes so it is likely inconsequential for most scenarios.
- Please share any issues you find!

## Future Upgrades:

- Auto download helper files.
- Filter based on community game ratings.
- GUI – (amateur programmer here so may take a bit)
- Handle extras like artwork.
- Please share any ideas you may have! I'm looking for suggestions that make Curator easier to use, results in a more arcade like collection, handles parent/clone selection better or additional filters that would be commonly used. However as a disclaimer, I'm not interested in supporting things without broad appeal or require the use of data sources that are not maintained or at risk of not being maintained in the near future. That would include most new projects.

## Helper Files (or additional required files):

- Weblinks are provided for all the download locations for the following:
  - MAME.exe
  - Rebuilder.exe
  - Languages.ini
  - Catver.ini
  
## Credits

- MAME Development Team - [Website](https://www.mamedev.org/)
- Roman Scherzer - Creator of Rebuilder - [Website](https://mamedev.emulab.it/clrmamepro/)
- progetto-SNAPS Team - Maintains the ini files along with many other MAME resources - [Website](https://www.progettosnaps.net/index.php)

