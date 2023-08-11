### Checklist

* Check the health of your operating system. Check that your system is out of viruses
* Disable file sharing during the process of exporting
* Install a fresh copy of WinsIsis
* Copy your databases to `C:\WINISIS\DATA` folder
* Open your databases. Verify the _total sum_ of records
* Check the _health_ of the databases inside WinIsis. Validate and debug your records. Found and amend any incompatible character that can generate corrupted data
* In case of deleted records, WinIsis will warn about if we should save it or not. Choose accordingly
* Choose previously which records should be exported
* Generate a `.fst` file (ie.: `export.fst`) with those fields choosen
* The name of the export file should be: `_____.fst` (6 letters maximum)
* Once the export process is done, import this file and choose the `.fst` file previously created (ie.: `export.fst`) 

