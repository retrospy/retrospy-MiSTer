# RetroSpy Update Database for the MiSTer Downloader

Database to keep RetroSpy for MiSTer up to date.

# NOTE: This should already be done by default in the new update_all script, but I haven't had a chance to verify it myself yet
Add the following in your download.ini at the root of your MiSTer's SD card.

```
[retrospy/retrospy-MiSTer]
db_url = https://raw.githubusercontent.com/retrospy/retrospy-MiSTer/db/db.json.zip
```
Once added simply run update_all to bring down the most recent version of RetroSpy for MiSTer.
