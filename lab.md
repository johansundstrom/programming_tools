# Skapa ett gränssnitt

Detta gränssnitt syftar till att vara tillgängligt för desktop, platta och smartphone. Tekniken bakom _Responsiv Design_ från Bootstrap används.

## Installera FTP-klienten i VS Code
* Välj extensions
* Sök upp och installera ```FTP-Simple```
* Öppna menyn med Shift + CTRL + P
* Skriv in ```ftp-simple```
* Välj ```CONFIG```
* Redigera filen _ftp-simple-temp.json_ med följande information och spara
```javascript
[
	{
		"name": "be9.asuscomm.com",
		"host": "be9.asuscomm.com",
		"port": 21,
		"type": "ftp",
		"username": "<givet användarnamn>",
		"password": "<aktuellt lösenord>",
		"path": "/",
		"autosave": true,
		"confirm": true
	}
]
```


## Bootstrap

* Sök upp ```Starter template``` på https://getbootstrap.com 
* Kopiera den till en tom fil i VS Code som heter ```index.html```
* Sök upp ```navbar```
