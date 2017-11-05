<# Skapa ett gränssnitt

Detta gränssnitt syftar till att vara tillgängligt för desktop, platta och smartphone. Tekniken bakom _Responsiv Design_ från Bootstrap används.

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
	"username": "<givet användarnamn>",
	"password": "<aktuellt lösenord>",
	"path": "/<givet användarnamn>",
	"autosave": true,
	"confirm": true
   }
]
```
* Spara och stäng filen

## Arbeta mot FTP-server
* Följande kommandon tillåts i FTP-Simple
|----------------------------------------------------------------------|
| config | Set the ftp connection information                          |
| create directory | Create a directory on ftp server                  |
| open | Open the file directly from ftp server and when you save upload it to the ftp server |
| save | File or directory upload to ftp server.(Available from the context menu) |
| download | Download the file or directory from ftp server to the workspace     |
| delete | Delete the file or directory directly from ftp server |
| diff | Compare a local file server file |
| Remote directory open to workspace | (Beta version) Open the direcotry directly on workspace from ftp server. Similar to remote  synchronization. (Caution : Remote delete a files is only possible using 'Delete' in the context menu) |

* Öppna _Command Palette_ med Shift + CTRL + P (eller F1)
* 


## Bootstrap

* Sök upp ```Starter template``` på https://getbootstrap.com 
* Kopiera den till en tom fil i VS Code som heter ```index.html```
* Sök upp ```navbar```
