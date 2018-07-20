# Rationale #
* Rescue, mining & clean up of an ancient database made on MicroIsis _circa_ mid-1990.
![microisis_welcome_page.png](https://bitbucket.org/repo/AjyxMg/images/1915817601-microisis_welcome_page.png)
* Implies firstly a [secure backup](https://bitbucket.org/imhicihu/terrae-database/src/dd7f229968c0f625060237281acc7a5c4c7d6dd7/To%20Do.md?at=master&fileviewer=file-view-default), then verify all the exported records, focusing on malformatted or incompatible characters (particularly diacritic accents). Particularly, this step was scrutinized under both offline and online tools. All the records migrated were saved in the safest way as possible. As final goal: amend all the typos found along the process.  
![informacion_multiusuario.png](https://bitbucket.org/repo/EBnakg/images/141072733-informacion_multiusuario.png)
![terrae-in-windows-environment.png](https://bitbucket.org/repo/EBnakg/images/4161797553-terrae-in-windows-environment.png)

### What is this repository for? ###

* Quick summary
     - Rescue, mining & clean up of an ancient database made on MicroIsis _circa_ mid-1990.
* Version 1.1

### How do I get set up? ###

* Summary of *our* set up:
     - Check our [WinIsis operating system test](https://bitbucket.org/imhicihu/winisis-migration/issues/1/software-winisis-compatibility-test)
     - [Windows 7 iso](https://www.microsoft.com/en-us/software-download/windows7)
          + once installed Windows 7 ISO via VirtualBox, install the [Windows XP Mode for Windows 7](https://www.microsoft.com/es-ar/download/details.aspx?id=8002): minimizing incompatibilities
	 - [WinIsis](http://biblio1.mdp.edu.ar/index2.php?pagina=recursos/wisis/winisis.php)
     - [VirtualBox](https://www.virtualbox.org/) (software that create a customize virtual environment for the sake of testing and creation of branches of experimentations. This allow us create custom actions according our needs)
     - [Google Sheets](http://spreadsheets.google.com/): once exported the data in`.csv` file format (courtesy to [db3iso](ftp://library.tomsk.ru/pub/isis/isis_products/db-iso/ver2/db3iso.zip)) open it in Google Sheets. Look for `corrupted or ignored` letters (ie: diacritic accent or cyrillic words) 
     - [csv reader](https://limonte.github.io/csv-viewer-online/)
     - [db3iso](ftp://library.tomsk.ru/pub/isis/isis_products/db-iso/ver2/db3iso.zip) 
     - [Beautiful Soap](https://www.crummy.com/software/BeautifulSoup/#Download): unencoding of unicode text to UTF-8 format specification. A kind of _swiss-army_ knife of encoding-unencoding text files

* Configuration
     - Vide [Exporting.md](https://bitbucket.org/imhicihu/terrae-database/src/eeb90385c59079bae5e286bad61c8e9fb57d2576/Exporting.md?at=master&fileviewer=file-view-default)
* Dependencies
     - Windows operating system. Check our [tests](https://bitbucket.org/imhicihu/winisis-migration/issues/1/software-winisis-compatibility-test)
     - WinIsis
     - csv file reader
* Deployment instructions
     - Install a fresh [WinIsis](http://www.unesco.org/new/en/communication-and-information/information-society/open-source-and-low-cost-technologies/information-processing-tools/cdsisis-database-software/cdsisis-for-window/) or a `.csv` reader on your computer

### Source ###

* Check them on [here](https://bitbucket.org/imhicihu/terrae-database/src)

### Issues ###

* Check them on [here](https://bitbucket.org/imhicihu/terrae-database/issues)

### Changelog ###

* Please check the [Commits](https://bitbucket.org/imhicihu/terrae-database/commits/) section for the current status

### Who do I talk to? ###

* Repo owner or admin
     - Contact `imhicihu` at `gmail` dot `com`
* Other community or team contact
     - Contact is _enable_ on the [board](https://bitbucket.org/imhicihu/terrae-database/addon/trello/trello-board) of this repo. (You need a [Trello](https://trello.com/) account)

### Copyright ###
![88x31.png](https://bitbucket.org/repo/4pKrXRd/images/3902704043-88x31.png)
This work is licensed under a [Creative Commons Attribution-ShareAlike 2.0 Generic License](http://creativecommons.org/licenses/by-sa/2.0/).

### Legal ###

* All trademarks are the property of their respective owners. 