# Skapa ett gränssnitt

Detta gränssnitt syftar till att vara tillgängligt för desktop, platta och smartphone. Tekniken bakom _Responsiv Design_ från Bootstrap används och är enklast möjliga.

## Installera FTP-klienten i VS Code
* Välj extensions
* Sök upp och installera ```FTP-Simple```
* Öppna _Command Palette_ med Shift + CTRL + P (eller F1)
* Skriv in ```ftp-simple```
* Välj ```CONFIG```
* Redigera filen _ftp-simple-temp.json_ med följande information
```javascript
[
   {
      "name": "B9",
      "host": "be9.asuscomm.com",
      "port": 21,
      "type": "ftp",
      "username": "<givet användarnamn>",
      "password": "<aktuellt lösenord>",
      "path": "/<givet användarnamn>",
      "autosave": true,
      "confirm": false
   }
]
```
* Spara och stäng filen

## Arbeta mot FTP-server
* Följande kommandon tillåts i FTP-Simple...

1. config - Set the ftp connection information
2. create directory - Create a directory on ftp server
1. open - Open the file directly from ftp server and when you save upload it to the ftp server
1. save - File or directory upload to ftp server (Available from the context menu)
1. download - Download the file or directory from ftp server to the workspace
1. delete - Delete the file or directory directly from ftp server
1. diff - Compare a local file server file
1. Remote directory open to workspace - (Beta version) Open the direcotry directly on workspace from ftp server. Similar to remote  synchronization. (Caution : Remote delete a files is only possible using 'Delete' in the context menu)

* Öppna _Command Palette_ med Shift + CTRL + P (eller F1)
* Välj kommandot: _remote directory open to workspace_
* Välj aktuell FTP-server
* Välj föreslagen sökväg som innehåller ditt namn

* Skapa filen index.html i VS Code's _workspace_. Så fort filen skapas i _workspace_ så sparas den på FTP-servern.



## Bootstrap

* Kopiera in ```Starter template``` från http://getbootstrap.com/docs/4.0/getting-started/introduction/#starter-template
* Kopiera ovanstående beskriven HTML-kod till ```index.html```
* Kopiera in ```navbar``` från https://getbootstrap.com/docs/4.0/components/navbar/#nav
* Spara filen ```index.html```
* I webbläsaren besök - http://be9.asuscomm.com/user/<givet användarnamn>
