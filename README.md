Komiks
======

This is just an idea for an comic book reader, after all current avaiable ones do not make me happy.

I want a comic book reader which is pretty much like netflix, and make it possible to continue reading right away.
Without delays and waiting, I should be able to pick the next one.


Here are some unordered thoughts:

Domain language
- Collection
- Serie
- Comic
- Page
- read
- location
- format

Functionality:
- Collection scanning
* should not impact reading (much)
* Scan should recognize remote / local file system
* Maybe different details when remote
* Only read the cover thumbnail
* Use CRC / checksums to recognise already loaded comics, even if renamed - also doubles
* Know last location in comic, every know one that is
* Recognised deleted comics, don't remove without a rule (ask/time)
* Have rules for the filename -> display name
* background scan
* Database

- Import from a location for offline viewing - Optimize for device size.
* Handle the offline file as a special thing by additionally linking the original entry.
* Have a way to manage downloads
- Cleanup collection
- Support different file formats by providing an interface, having a way to add additional file types easy later on
- dotnet core 5
- Dependency injection
- generic host
- ImageSharp
- Category?
- Netflix like interface
* being able to continue reading one of the recently read comics
* My list (want to read next)
* search
- Settings (manga mode, fit zo height/width etc)
- Night mode
- Export lists
- Mark /unmark as read
- Classify as PG/18+ etc
- Multiple profiles
- Open source, but paid in the Microsoft store
- Multi platform (MAUI)

MVP
- Scan & index into database
- Quick start
- CBZ
- Fullscreen reading without resizing (but rotate)
