![stability-wip](../images/3278295154-status_archived.png)
![internaluse-green](../images/3847436881-internal_use_stable.png)
![issues-open](../images/2944199103-issues_open.png)

# Rationale #
* Rescue, mining & clean up of an [ancient database](http://rescatandoterrae.tumblr.com/) made on MicroIsis _circa_ mid-1990.
![microisis_welcome_page.png](../images/1915817601-microisis_welcome_page.png)
* Implies firstly a [secure backup](https://bitbucket.org/imhicihu/terrae-database/src/dd7f229968c0f625060237281acc7a5c4c7d6dd7/To%20Do.md?at=master&fileviewer=file-view-default), then verify all the exported records, focusing on malformed or incompatible characters (particularly diacritic accents). Particularly, this step was scrutinized under both offline and online tools. All the records migrated were saved in the safest way as possible. As final goal: amend all the typos found along the process.  
![informacion_multiusuario.png](../images/141072733-informacion_multiusuario.png)
![terrae-in-windows-environment.png](https://bitbucket.org/repo/EBnakg/images/4161797553-terrae-in-windows-environment.png)

### What is this repository for? ###

* Quick summary
     - Rescue, mining & clean up of an ancient database made on MicroIsis _circa_ mid-1990.

### How do I get set up? ###

* Summary of *our* set up:
     - Check our [WinIsis operating system test](https://bitbucket.org/imhicihu/winisis-migration/issues/1/software-winisis-compatibility-test)
     - [Windows 7 iso](https://www.microsoft.com/en-us/software-download/windows7)
          + once installed Windows 7 ISO via VirtualBox, install the [Windows XP Mode for Windows 7](https://www.microsoft.com/es-ar/download/details.aspx?id=8002): minimizing incompatibilities
     - [WinIsis v.1.5.3 Build 3](https://www.dropbox.com/s/44vpnjcs6n569h9/winisis-Windows-1.5.3.zip?dl=0): shared link via [Experiencia Aguapey](https://aguapeyexperience.wordpress.com/recursos-descargas/)
     - [VirtualBox](https://www.virtualbox.org/) (software that create a customize virtual environment for the sake of testing and creation of branches of experimentations. This allow us create custom actions according our needs)
     ![windowsxpvirtualized.jpg](../images/3264682538-windowsxpvirtualized.jpg)
     - [Google Sheets](http://spreadsheets.google.com/): once exported the data in`.csv` file format (courtesy to [db3iso](ftp://library.tomsk.ru/pub/isis/isis_products/db-iso/ver2/db3iso.zip)) open it in Google Sheets. Look for `corrupted or ignored` letters (ie: diacritic accent or cyrillic words) 
     - [csv reader](https://limonte.github.io/csv-viewer-online/)
     - [db3iso](ftp://library.tomsk.ru/pub/isis/isis_products/db-iso/ver2/db3iso.zip) 
     - [Beautiful Soap](https://www.crummy.com/software/BeautifulSoup/#Download): unencoding of unicode text to UTF-8 format specification. A kind of _swiss-army_ knife of encoding-unencoding text files

* Configuration
     - Vide [Exporting.md](https://bitbucket.org/imhicihu/terrae-database/src/8c67f83f89d3c1f63c78bc070c67da373828fe91/Exporting.md?at=master&fileviewer=file-view-default)
     - Vide [Exportación.md](https://bitbucket.org/imhicihu/terrae-database/src/master/Exportando/Exportaci%C3%B3n.md)
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

### Copyright ###
![88x31.png](../images/3902704043-88x31.png)
This work is licensed under a [Creative Commons Attribution-ShareAlike 2.0 Generic License](http://creativecommons.org/licenses/by-sa/2.0/).

### Legal ###

* All trademarks are the property of their respective owners. 